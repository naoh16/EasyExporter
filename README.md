# EasyExporter

MS PowerPoint Addin for exporting slides or pictures.

- Export selected slides as a PDF
- Export selected slides as PNGs, JPEGs, EMFs, or PDFs as file-per-slide.
- Export selected images as a PNG, JPEG, EMF, or SVG.
 
<img width="841" height="102" alt="ss_easy_exporter" src="https://github.com/user-attachments/assets/774e6cd1-d9e5-4896-b2af-ccf92bd31f67" />

# For developer

## Flow

- Update .pptm
- Save as .ppam

### Update .pptm

#### Update macros

- Alt + F11

#### Update Custom UI

- Edit customUI/customUI.xml
- Open *.pptm by 7-zip
  - or, you can use an archiver that can open the file as ZIP container.
- Replace customUI/customUI.xml in the .pptm (.zip) file

### Save as .ppam

- Open .pptm
- Save as .ppam

NOTE: You cannot edit .ppam file. So don't forget to keep original pptm file!
