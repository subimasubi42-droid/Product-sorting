# Product-sorting
Automatic Product Sorting System uses RFID, Arduino Uno, and a Servo Motor to automatically identify and sort parcels. The RFID reader reads the parcel information, Arduino checks the destination, and the servo motor directs the parcel to the correct section. This system reduces manual work, saves time, and minimizes sorting errors. �

Slide 1 – PRODUCT SORTING

Automatic Product Sorting System Using Arduino and RFID

Team CORECREW
M. Mithra • Subiksha S. • Aadhil Ahammed P. S. • Lalith P.
Department of Electrical and Electronics Engineering


---

Slide 2 – PROBLEM STATEMENT

Current Situation

Courier and logistics companies handle many parcels for different destinations.
Manual sorting can take more time.
Parcels may also be placed in the wrong destination section.

Problems Identified

Manual sorting takes more time.

Parcels may be placed in the wrong destination.

Human errors can delay delivery.

Large numbers of parcels increase the workload.

Continuous manual checking requires more effort. 



---

Slide 3 – PROPOSED SOLUTION & OBJECTIVES

Proposed Solution

We developed an Automatic Product Sorting System using Arduino Uno, RFID and Servo Motor.

The RFID reader reads the parcel tag.
Arduino checks the destination.
The servo motor moves the parcel to the correct section.

Objectives

Automate parcel sorting.

Reduce manual work.

Reduce parcel mix-ups.

Reduce sorting errors.

Improve sorting efficiency.

Place parcels in the correct destination. 



---

Slide 4 – HARDWARE COMPONENTS

Arduino Uno

It is the main controller.

RFID RC522

It reads the RFID tag.

RFID Tags

They give each parcel a unique identification.

Servo Motor

It controls the sorting mechanism.

Conveyor / Platform

It supports or moves the parcel.

DC Motor / Driver

It drives the conveyor, if used.

Power Supply

It provides electrical power.

Connecting Wires

They make the electrical connections. 


---

Slide 5 – SYSTEM BLOCK DIAGRAM

Parcel
↓
RFID RC522
↓
Arduino Uno
↓
Destination Check
↓
Servo Motor
↓
Correct Destination

Sorting Process

RFID Detection → Arduino Processing → Destination Identification → Servo Sorting

Destinations:

Erode Section

Salem Section

Coimbatore Section 



---

Slide 6 – WORKING PRINCIPLE

Step 1: Parcel is placed on the sorting platform.

Step 2: RFID RC522 detects the RFID tag.

Step 3: RFID UID is sent to Arduino Uno.

Step 4: Arduino checks the UID with the programmed destination.

Step 5: Arduino sends a signal to the servo motor.

Step 6: Servo motor moves the sorting mechanism to the required section.

Step 7: Parcel is sent to the correct destination.

Step 8: Servo motor comes back to its original position. 


---

Slide 7 – RFID MAPPING & CONNECTION

Destination Mapping

Tag 1 → Erode → Position 1
Tag 2 → Salem → Position 2
Tag 3 → Coimbatore → Position 3

Replace Tag 1, Tag 2 and Tag 3 with the actual RFID UIDs used in the prototype.

RC522 → Arduino Uno

SDA → D10

SCK → D13

MOSI → D11

MISO → D12

RST → D9

GND → GND

3.3V → 3.3V

Servo Signal → D6 



---

Slide 8 – PROTOTYPE, TESTING & RESULT

Prototype

RFID Detection Unit
↓
Arduino Control Unit
↓
Servo Sorting Mechanism
↓
Destination Sections

Testing

Test 1: Erode
Expected: Erode section

Test 2: Salem
Expected: Salem section

Test 3: Coimbatore
Expected: Coimbatore section

Result

The prototype identifies the destination automatically and sorts the parcel using the servo motor according to the RFID information. 


---

Slide 9 – ADVANTAGES, APPLICATIONS & FUTURE SCOPE

Advantages

Reduces manual work.

Reduces parcel mix-ups.

Provides faster sorting.

Uses RFID for identification.

Low-cost prototype.

Easy to operate.


Applications

Courier and logistics centers

Warehouses

E-commerce parcel handling

Distribution centers

Automated material handling


Future Scope

Automatic conveyor system

More destinations

LCD/OLED display

IoT-based tracking

Automatic parcel counting

Barcode/QR integration 



---

Slide 10 – THANK YOU

PRODUCT SORTING
Automatic Product Sorting System
TEAM CORECREW | EEE 

