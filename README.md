# SUMMARIZE PDF FILES

Imagine you are reading a 10 page document such as a research paper or an agreement and that you have highlighted few important points in the document. This program allows you to extract those important points and save it as a new PDF file. This software also comes handy if you are reading a technical book - you can summarize definitions in a single PDF file!

## WHY THIS SOFTWARE?

If you have Adobe Pro, you can use inbuilt feature to extract highlighted text. This feature is not available in Adobe Reader DC which is free. Sumnotes is again an excellent tool to extract highlighted text but in the free version you are only allowed 10 annotations per download. Foxit Reader Version: 9.0.1.1049 allows extraction of highlighted text in a new PDF file and is free! But there are few disadvantages such as,

1. If the notes are sorted by pages, annotations on a new page of the original PDF are not continued on the same page in summarized PDF file. This results in wastage of space.
2. The text is not justified.
3. Along with each extracted text, you are supplied with metadata which results in more wastage.

You can see an example when you download the file - FoxitSummary.pdf in Example folder.

Because of the reasons mentioned above, I decided to write this software so that people can extract all annotations for free. The summary file is presentable as well - compare SummarizePDF.pdf and FoxitSummary.pdf.

The project is under MIT License.

## HOW TO USE THIS SOFTWARE?

1. Download and install [Foxit Reader] (https://www.foxitsoftware.com/pdf-reader/)
2. After completing installion, open any PDF file in Foxit Reader.
3. Click on *File* in menu bar and then click on *Preferences*.
4. Click on *Commenting* and under *Making Comments* tick *Copy selected text into Highlight, Squiggly, Underline and Strikeout comment popups*.
5. Click on *OK*.
6. Download SummarizePDF software. The *lib* folder in *dist* folder contains JAVA libraries needed by the software file *SummarizePDF.jar* to function. Hence, you must always run the software file in the same directory as that of *lib* folder. You can create a shortcut for *SummarizePDF.jar* and move it whatever location on your computer.
7. Click on *SummarizePDF.jar* or the shortcut file.
8. In the GUI, click on *Choose File* to select the PDF file.
9. The path of the selected file is shown and the name of the summary file is also shown. The name can be edited.
10. The user can also select font size. Default size is 8.
11. Click on *Summarize* to extract highlighted text.
12. If the PDF file does not contain any highlights, then no summary file is created.
13. If the PDF file contains highlighted text, a summary file is created in the same *dist* folder.

## KNOWN ISSUES

1. The software only works on text - tables and images are not supported.
2. The software does not work with Adode Reader DC.
