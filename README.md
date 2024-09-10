# Fraud Detection in Retail Transactions Using Computer Vision

This repository contains an end-to-end computer vision solution designed to detect potential fraud during cash transactions in a retail environment. The project identifies cases where a cashier fails to generate or provide an invoice after a cash transaction. The solution includes:

- **Computer Vision Model**: Detects and recognizes key actions related to cash transactions and invoice generation.
- **Custom API**: Simulates invoice generation after cash transactions, integrated with a MongoDB database to log transaction details.
- **Real-time Fraud Detection**: Flags potential fraud when an invoice is not generated within 15 seconds after a cash transaction.
- **Dynamic Video Counters**: Overlays real-time counters on the video output to show:
  - Number of cash transactions detected.
  - Number of invoices generated.
  - Fraud status for each transaction.

### Key Components:
1. **Data Engineering**: Frame extraction, labeling, and augmentation from video footage of cash transactions.
2. **Computer Vision Model**: Detects cash transactions and invoice generation using object detection and action recognition techniques.
3. **API Development**: API to simulate invoice generation, trigger fraud detection, and store transaction records in MongoDB.
4. **MongoDB Integration**: Logs details of each transaction, including timestamps, invoice status, and fraud flags.
5. **Video Output**: Processes videos with real-time counters and fraud detection status overlaid on the frames.

### Deliverables:
- Video output with dynamic counters for cash transactions, invoices, and fraud detection.
- MongoDB database storing detailed transaction records.
