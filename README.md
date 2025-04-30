# Annotations of Pathological Images Using QuPath and Fiji

This project provides a structured approach for annotating pathological images using **QuPath** and **Fiji (ImageJ)**. These tools are widely used in digital pathology for tasks such as cell segmentation, region annotation, and biomarker quantification.

---

## 🧪 Tools Used

- **[QuPath](https://qupath.github.io/)**: An open-source software platform for bioimage analysis.
- **[Fiji (ImageJ)](https://fiji.sc/)**: A distribution of ImageJ with a focus on biological image analysis, bundled with useful plugins.

---

## 📁 Project Structure


---

## 🔍 Workflow Overview

1. **Image Import**  
   Load whole-slide images (WSIs) into QuPath or Fiji.

2. **Preprocessing**  
   - Color deconvolution (H&E, IHC)
   - Background correction
   - Tiling (if needed for Fiji)

3. **Annotation**  
   - Manual: Use drawing tools in QuPath or ROI Manager in Fiji.
   - Automated: Use cell detection, pixel classifiers, or scripts.

4. **Segmentation and Analysis**  
   - Nuclei or cell segmentation
   - Quantification of features (area, intensity, count)

5. **Export Results**  
   - Export annotations in GeoJSON, JSON, or CSV formats.
   - Save segmented masks or overlays for further analysis.

---

## 🛠 Example Scripts

- `qupath_cell_detection.groovy`: Automates cell detection in QuPath.
- `fiji_macro_segmentation.ijm`: Fiji macro for ROI-based segmentation.
- `convert_annotations.py`: Converts annotation formats between tools.

---

## 🧾 Requirements

- Java 8+ (for QuPath and Fiji)
- Python 3.7+ (if using scripts)
- QuPath v0.4.0+
- Fiji with Bio-Formats plugin

---

## 📘 Documentation

- [QuPath Wiki](https://qupath.readthedocs.io/)
- [Fiji Documentation](https://imagej.net/software/fiji/)
- [Bio-Formats](https://www.openmicroscopy.org/bio-formats/)

---

## 📷 Sample Outputs

| Input Image | Annotated Image |
|-------------|-----------------|
| ![H&E Image]![Image](https://github.com/user-attachments/assets/8576c1f3-b665-4c1d-890d-37bfdf60ccd2) | ![Annotated]![Image](https://github.com/user-attachments/assets/6017018d-7f1e-4044-9205-ed963cc0b283) |

---

## 📄 License

This project is open-source under the MIT License.

---

## 🙋‍♀️ Contributions

Contributions, suggestions, and feedback are welcome! Please open an issue or submit a pull request.
