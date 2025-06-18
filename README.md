# fido-ai
A proof-of-concept app to make it easier to try out Artificial Intelligence for making accessible publications

## Background
In late 2024 DAISY Consortium conducted a survey of AI Use by DAISY Members. This indicated high levels of interest in the adoption of AI, but the cost of AI services and the lack of technical expertise were both identified as potential barriers to adoption. 

To support our members’ desire to experiment and innovate we have developed a proof-of-concept app to enable DAISY members to try out Artificial Intelligence for some of the use cases they have identified. This includes the use of AI for PDF conversion, converting scientific expressions to MathML, image description, and metadata generation. The app makes it simpler to evaluate the capabilities of a range of online and offline AI services, and experiment with different prompts to suit different requirements. To facilitate a real-world evaluation of applications of AI the app is a working tool to conduct file conversions.

On the basis of member evaluations, we can consider integrating some of these artificial intelligence services into DAISY production tools like the DAISY Pipeline.

## Fido Feature List
-	Accessible desktop app for Windows and Mac (possibly Linux).
-	Supports input and output of input and output of various formats (EPUB, HTML, Markdown, Open Document Format, Word).
-	Offers different methods for conversion from PDF, including offline conversion (PyMuPDF) and cloud-based AI (Marker, Mistral AI, and Mathpix).
-	Conversions include features especially important for accessible book production, including metadata and page markup.
-	Generates draft image descriptions using GenAI (from Anthropic, Google, and OpenAI). This can be for individual images, all images in a folder, Word document or PowerPoint deck.
-	The user can specify image classifications and associated prompts (to better handle different types of images, eg diagram, map, infographic, chart, table, timeline, photograph, etc).
-	Can be used to generate draft metadata using GenAI.
-	Gen-AI prompts can be customised by the user for language, writing style, etc to meet house style, cultural and target audience requirements.
-	The user can select from a choice of Gen-AI services for preferred functionality, costs and policy compliance.
-	Gen-AI services from Anthropic, Google, OpenAI and DeepSeek are currently supported, with local GenAI support at the research stage.

## Questions and Answers
Q: What AI did DAISY develop?

A: None. We made a user interface to enable our members to experiment with different AI possibilities.

Q: What scripts are supported in the OCR used in the PDF conversions?

A: Early tests indicate good OCR results with Arabic, Cyrillic, Devanagari, Latin, and Quốc Ngữ scripts.

Q: What about math expressions?

A: We have included conversion solutions that claim to handle scientific expressions well, with the capability to convert images to LaTeX, MathML and OMML. Early feedback is promising.

Q: How much will the AI services cost?

A: The costs differ between the various services. As an example, we calculate that to convert 10,000 PDF pages using Mistral AI is around $10, and to create draft descriptions for 1,000 images using Google Gemini is around $15. These costs need validation. Understanding the costs is an important part of the evaluations our members will do.

Q: How does this integrate with other DAISY tools?

A: Whilst the conversions look very promising, please understand that Fido is not a production quality app. The outputs will allow members to experiment and evaluate the results of the AI supported conversions. After human in the loop proof-reading, editing and formatting, the Word files could be used as an input to the DAISY Pipeline, WordToEPUB, or other tools of your choosing.

Q: Why Fido?

A: The acronym stands for Files In, Documents Out. It also a well known name for a dog, derived from the Latin word fidelis meaning "faithful. This explains the app’s icon, some doggy pawprints in the DAISY blue colour. Abe Lincoln’s famous dog was called Fido, and there is a [rap song](https://youtu.be/E4GXQ3ZlDf4?si=OtxaB3peklX4Y1HX) about the Italian dog of the same name who waited for 14 years after his master’s death. We hope that Fido is a friendly companion as you explore the possibilities and limitations of AI for accessible publishing.
