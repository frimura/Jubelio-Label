Jubelio Label Code Printer (browser version)

1. Open index.html in Chrome while connected to the internet.
2. Drop a Jubelio shipping-label PDF into the page.
3. Review the page thumbnails and the status report.
4. The print dialog opens automatically when processing finishes. You can also click "Print processed labels" again, or "Download processed PDF" to save an edited PDF.

Notes:
- The page uses PDF.js and pdf-lib loaded from public CDNs; the PDF itself is processed locally and is not uploaded.
- Because this first version recognizes text labels such as "No Pesanan" or "Order Id", verify the status report before printing.
- The print-preview path rasterizes pages at 2x resolution for printing. Use the downloaded processed PDF if preserving vector/barcode sharpness is important; it adds the code directly to the PDF.
- The added code is positioned near the bottom margin. Check one test page before printing a large batch.
- This is a prototype, not a security-audited product.
