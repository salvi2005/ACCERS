# ACCERS
Description:
The Palm Payment System is a real-time, contactless payment solution that leverages computer vision and hand recognition for secure transactions. Using a standard webcam and MediaPipe Hands, the system detects and scans a user's palm to authorize payments, providing a futuristic and hygienic alternative to card swipes or cash.

Key Features:

Real-time Hand Detection: Uses MediaPipe to track hand landmarks and ensure accurate palm detection.

State-based Transaction Flow: Implements a multi-stage process: WAITING → SCANNING → VERIFYING → APPROVED → CONFIRMED → SUCCESS.

Interactive UI & Animations: Visual indicators, scanning progress bars, verification steps, and dynamic overlays enhance user experience.

Transaction Management: Generates unique transaction IDs, displays customer and merchant details, and tracks transaction confirmation.

Keyboard Integration: Allows confirmation of payments via key press (Y) and exiting (Q).

Receipt Generation: Automatically prints a detailed transaction receipt with date, merchant info, customer info, and transaction amount.

FPS & Performance Tracking: Monitors real-time FPS to ensure smooth operation.

Technologies Used:

Python 3

OpenCV for video capture and GUI overlay

MediaPipe for hand landmark detection

NumPy for calculations and animations

UUID & datetime for transaction management

Use Case:
This system can be deployed at retail stores, vending machines, or payment terminals where contactless and secure transactions are desired. It ensures a hygienic and futuristic payment experience while providing real-time verification and receipt generation.

Optional Enhancements:

Integrate with actual payment gateways for real transactions.

Support multiple hand recognition for multi-user payment.

Add voice prompts or haptic feedback for enhanced UX.
