# Content Provisioning Guidelines
*As you gather together content for your new website, here are some guidelines for what you should create and how it should be arranged.*

**Goal**: To create a smoother development process by conveying content provisioning best practices.

**Audience**: Clients who are providing non-HTML content to their developers.

## Text
Ideally, any text provided should be in the plain text format (.txt file). Notepad on Windows and TextEdit on Mac can both output these files. Plain text is exactly what is sounds like – just text, without formatting or images, and content in this format will be imported into your site with 100% fidelity.

Please create a separate file for each page of web content.

### Using MS Word
If you need more robust formatting than plain text can provide, you can use Microsoft Word. Word’s code isn’t written to web standards, so importing Word content to your website may produce undesirable results, such as excessive spacing between your paragraphs or large chunks of content being bolded or jibberish. 

To minimize this risk, use only Word’s basic formatting features: bold, italicize, underline, and heading assignments. Do not include images or tables in your Word files, and don’t worry about font, font size, or spacing – this is all handled in the website’s style code.

The same applies for Google Docs, and most other Office-style text editors.

**Note**: If you want to explore a different way to write, look into markdown. MD files are completely standards compliant and very easy to import into your website. I personally recommend iA Writer.

## Images
Standard web image formats are JPEG and PNG. Use JPEG for photos and PNG for graphic material such as logos. 80% compression on your JPEG images is probably fine.

Images online are 72 DPI, as opposed to 300 DPI print images.
A width of 1200px is usually more than enough, since the content area on most webpages is less than 800px.

Images should almost always each be under 1mb in size.

The name of your image is visible to your site’s visitors, so try to give it a relevant filename. 'fido-on-the-beach.jpg' is much more meaningful than 'IMG000061.jpg'.

If you’re purchasing stock photography, the ‘small’ size is usually sufficient, but check with your developer to be sure.

**Note**: Retina support is a separate discussion. If you want to optimize your site imagery for retina devices, talk to your developer before gathering your content.

## Documents
For documents, PDFs are the preferred web file format, since they load consistently across platforms and most modern browsers now show them natively. You can turn any document into a PDF using a Mac or CutePDF on Windows. Word files (.doc and .docx) are discouraged since they require additional software for the user to view them.

## Video
On most websites, you want to host your video through an external provider, such as YouTube or Vimeo. This will reduce your bandwidth cost while allowing the videos to load faster, served up by these companies’ powerful servers. Video hosted on these sites is also compatible with most browsers/devices, without any extra work. 

## Audio
Audio can typically be hosted onsite. The optimal format and bitrate will depend on project constraints. 