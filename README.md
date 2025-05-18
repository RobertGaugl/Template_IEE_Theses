# Template for Bachelor’s and Master’s Theses
This document is the official LaTeX template of the Institute of Electricity Economics and Energy Innovation (IEE) for Bachelor’s and Master’s theses. It is designed to help students structure and format their work according to the institute’s academic and formatting standards.

The LaTeX template was created with Overleaf. TU Graz provides free Overleaf licenses, so it is strongly recommended to use Overleaf for your work. However, it should also work with other LaTeX editors.

<p align="center">
  <img src="figures/Title_page.png" alt="Title_page" width="40%" /></br>
  <b>Figure 1.</b> Title page of the template.
</p>

## How to use?
1) Download the ZIP file by clicking the green "**Code**" button and selecting "**Download ZIP**".
2) Depending on your LaTeX editor:
   - **Overleaf**: Click **New Project** > **Upload Project**, then select the downloaded ZIP file.
   - **Other LaTeX editors**: Extract the ZIP file and open the files in your preferred editor.
3) Read the content of the template carefully. It explains the rules for writing a bachelor's or master's thesis at the IEE and provides helpful tips and tricks.

## Structure of the template

At the top of the main.tex file, you'll find the Metadata section, where you need to configure several settings (e.g., specifying whether it's a Bachelor's or Master's thesis, selecting the language, which will affect the title page and other headers and formatting options). Additionally, you will need to enter your name, the title of your thesis, and other relevant information.

Following the Metadata section, the main.tex file defines the page layout, loads the preamble.tex (which contains all the package definitions), and also includes the subsections.
The subsections are in the folder chapters and are organized divided into 3 main blocks:
- AXX_: These chapters contain pre-content (Title page, Acknowledgments, Abstract, Table of Contents).
- BXX_: Main content of the work.
- CXX_: These chapters contain after-content (Abbreviations, Bibliography, possibly Appendix).

## Release Notes
- **2025-04-08:**
   - Automatic adjustment of spacing between title page elements to ensure an aesthetically pleasing layout, even with titles of up to five lines.
- **2025-04-05:**
   - Translate content to English. Add automatic switching between Bachelor's and Master's theses, as well as between German and English for the title page and other automatic headers and settings.
- **2025-04-03:**
   - Remove affidavit as it is not allowed anymore because of data protection.
- **2025-03-28:**
   - Update the title page to include the name of the degree program. Include new subsection Revision nach Korrektur.
- **2022-08-09:**
   - Fixed a bug that caused missing page breaks and empty pages