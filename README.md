# PACE-ADA
AI Document Automation

### Dependencies
| Solution | Description   |
|--|--|
| Document automation base kit | The base solution from Microsoft. For more information on how to install it in your environment, see https://learn.microsoft.com/en-us/ai-builder/doc-automation |
| Canvas Translations | Contains the translation tables for the Document Automation Application Canvas app |


### How to Install
1) Install the Document automation base kit solution into your environment
2) Import the CanvasTranslations/CanvasTranslations_1_0_0_3.zip solution into your environment
3) Import the CanvasTranslations/ADATranslationsData.xlsx data into the pace_canvastranslation table
4) Create a DevOps pipeline with this repository as a source, and $(System.DefaultWorkingDirectory)/Documenttoolkit/Solution as the Solution Input File

![image](https://github.com/user-attachments/assets/f040b716-76c3-43b2-ab79-0d528b80c3e0)

5) Run the pipeline to import the latest version of the ADA solution
