# Hi, I'm ylgjob 👋

I build small, free web tools that run entirely in the browser — no uploads, no sign-up.

## Projects

### [TNPSC Signature Compressor](https://tnpscsignaturecompressor.com/)
Photo and signature tool for Tamil Nadu (TNPSC) exam applications.
- Signature: resize to 400 × 133 px and compress to a 10–20 KB JPG
- Photo: crop to 3.5 × 4.5 cm, add name and photo date, compress to 20–50 KB
- Size guide: [TNPSC photo & signature size](https://tnpscsignaturecompressor.com/tnpsc-photo-signature-size/)

### [FormResizer](https://formresizer.com/)
Resize signatures and photos to the exact KB and pixel size an Indian online application form asks for.

## How they're built
Next.js static export, client-side image processing (Canvas / WebAssembly). Every output file is decoded again so the size, dimensions and DPI shown are the real ones.
