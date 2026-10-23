# JERVISH Business Suite — Final GitHub Edition

A free, static, local-first business/invoice manager designed to deploy directly from a GitHub repository.

## Deploy on GitHub Pages

1. Create a GitHub repository.
2. Upload **all files in this folder** to the repository root.
3. Open **Settings → Pages**.
4. Select **Deploy from a branch**.
5. Select your `main` branch and `/ (root)` folder.
6. Save and open the generated Pages URL.

No Node.js, npm, database, PHP or server is required for the GitHub Pages edition.

## PDF

The invoice/quotation viewer has a real **Download PDF** button using `html2pdf.js` from a public CDN. If the PDF library cannot be loaded, the app automatically falls back to the browser print dialog.

## Data

The app stores business data in the browser's localStorage. Use **Backup / Restore → Download Backup** regularly. Clearing browser/site data can remove local records.

## Included

- Dashboard
- Sales invoices
- Quotations
- Quotation → invoice conversion
- Party/client master
- Item/product master
- Automatic GST mode: CGST + SGST for known same-state parties, IGST for known different-state parties
- HSN/SAC
- Quantity + unit
- Bank details
- Invoice/quotation PDF download
- Print fallback
- Amount in words
- Round-up and totals
- Payments and outstanding status
- Expenses / purchases
- Business settings and branding
- JSON backup / restore
- Responsive layout
- A4 reference-inspired invoice design

## Important

This is an independent invoicing application. It does not claim to be an official GST filing/e-invoicing product and does not connect to GSTN, payment gateways or bank feeds. Verify tax treatment, HSN/SAC, place of supply and invoice compliance for your actual business before relying on generated documents.
