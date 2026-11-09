# Hi, I'm ylgjob 👋

I build small, free web tools that run entirely in the browser — no uploads, no sign-up.

## Projects

### [AttestedPhoto](https://attestedphoto.com/)
Self attested photos and documents for Indian application forms, made on your phone or laptop.
- Photo: add your signature, name and date, then crop and compress to the size the form asks for (for example 240 × 320 px, 20–50 KB)
- Documents: add "Self Attested" or "True Copy", a signature and the date to every page of a PDF or scan
- Also: [photo and signature merge](https://attestedphoto.com/photo-signature-merge/), [Aadhaar front and back on one page](https://attestedphoto.com/aadhaar-card-front-and-back-merge/)
- Guide: [How to self attest a document](https://attestedphoto.com/how-to-self-attest-a-document/)

### [TNPSC Signature Compressor](https://tnpscsignaturecompressor.com/)
Photo and signature tool for Tamil Nadu (TNPSC) exam applications.
- Signature: resize to 400 × 133 px and compress to a 10–20 KB JPG
- Photo: crop to 3.5 × 4.5 cm, add name and photo date, compress to 20–50 KB
- Size guide: [TNPSC photo & signature size](https://tnpscsignaturecompressor.com/tnpsc-photo-signature-size/)

### [FormResizer](https://formresizer.com/)
Resize signatures and photos to the exact KB and pixel size an Indian online application form asks for.

## How they're built
Next.js static export, client-side image processing (Canvas / WebAssembly). Every output file is decoded again so the size, dimensions and DPI shown are the real ones.
