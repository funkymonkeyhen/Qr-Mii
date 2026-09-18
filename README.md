<h1>QR Mii</h1>
<p>This is a project where you can make Mii QR Codes from your wii</p>
<hr>
<p></p>Third-party code included</p>
`source/qrcodegen.c/h` - Nayuki's QR Code generator library (MIT license).
This is the same QR library used by the MiiPort homebrew project.
`source/aes.c/h` - tiny-AES-c (public domain / Unlicense), used only for
its raw AES-128 block primitive; the actual CCM logic on top of it is
hand-written to match the 3DS's specific implementation.
