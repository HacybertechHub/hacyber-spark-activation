## Spark Driver™ Onboarding - Enrollment Portal
A polished, high-intent frontend UI template for a gig economy delivery driver onboarding system. This portal is designed to streamline independent contractor activation while maintaining compliance and professional branding.
# 🚀 Overview
This repository contains a single-page, responsive enrollment surface optimized for the "Time-to-First-Gig" metric.[1] It features a standardized data-parsing layout for driver credentials and a mandatory fee-processing component to handle expedited background check workflows.
# ✨ Key Features
• Standardized Identity Display: A structured block for rendering parsed ID data, specifically optimized for Florida Class E credentials and Document Discriminators (DD).[2, 3]
• Priority Processing UI: A high-visibility "Important Notice" block for collecting the $120.00 Mandatory Administrative Fee. This fee accounts for expedited API pass-through costs from county/state repositories.[4, 5]
• System Status Indicators: A sticky live-status bar to maintain trust and transparency during active sessions.[1]
• Vercel-Ready Architecture: Zero-configuration deployment for static hosting.
• Brand Consistency: CSS-driven animated Spark icon and official corporate footer mapping back to 702 SW 8th St, Bentonville, AR.
# 🛠️ Quick Start
1. Deployment
To get this live in under 60 seconds:
1.	Fork this repository.
2.	Log into Vercel and import the repo.
3.	Ensure your main file is named index.html in the root directory.
2. Local Customization
To update the driver details or fee amount, edit the following sections in index.html:
• Fee Amount: Located in the .notice-body div.
• ID Data: Update the .details-text block with the applicant's scanned information.
# ⚖️ Legal & Compliance
This portal is a UI/UX template and does not process real-time financial transactions out of the box.
• Privacy: No PII (Personally Identifiable Information) is stored on the client side.
• Fee Justification: The $120.00 fee is presented as a mandatory surcharge to cover third-party pass-through costs (MVR, Criminal, and Identity verification).[4, 6]
• Disclaimer: All information displayed in the "Submitted ID Information" block is classified as user-provided and remains subject to final verification.[7, 8]
# 📜 License
This project is licensed under the MIT License—see the(LICENSE) file for details.
