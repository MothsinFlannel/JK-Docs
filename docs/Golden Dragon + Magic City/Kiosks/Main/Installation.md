---
title: Installation
nav_order: 4
layout: default
parent: Kiosks
---

## Confirm the Kiosk PC is connected to all hardware according to the reference below.

<img src="../Images/Installation/GDMC%20Reload%20Kiosk%20-%20Technician%20Instructions%20-%20IMG1.jpg" alt="Alt text" style="width: 64%; margin-right: 2px;">
<img src="../Images/Installation/GDMC%20Reload%20Kiosk%20-%20Technician%20Instructions%20-%20IMG2.jpg" alt="Alt text" style="width: 34%;">



## Connect the main power and confirm device is turned on.

<img src="../Images/Installation/GDMC%20Reload%20Kiosk%20-%20Technician%20Instructions%20-%20IMG3.jpg" alt="Alt text" style="width: 70%;">

## Internet Setup

If no wired internet connections are available, the kiosk can connect to WiFi.

Start by connecting a keyboard and pressing the Windows key. This will display the Windows
search window and the taskbar.

Select the Wireless icon to select a network within range.

<img src="../Images/Installation/GDMC%20Reload%20Kiosk%20-%20Technician%20Instructions%20-%20IMG4.jpg" alt="Alt text" style="width: 70%;">

## Kiosk Binding

##### (THIS PROCESS SHOULD BE COMPLETED IN THE WAREHOUSE. IF THE KIOSK DOES NOT DISPLAY THE SCREEN BELOW, PROCEED TO “CONFIGURE KIOSK” SECTION.

Once powered on and connected to the internet, a Device ID will appear on the screen, please
take a picture of the Device ID and forward to the Software Team.

Click the "VERIFY" button on the machine to verify the binding status.

<img src="../Images/Installation/GDMC%20Reload%20Kiosk%20-%20Technician%20Instructions%20-%20IMG5.jpg" alt="Alt text" style="width: 70%;">

When the binding of Golden Dragon and Magic City is successful, the Logo will display
"PASS". If the binding fails or has not arranged on the backend, it will display "FAIL".
(If "FAIL" is displayed, please contact the authorized personnel of the Distributor or Agent to
confirm the binding status. Wait for the configuration to be completed, and then click the
"RETRY VERIFY" button to verify the binding again.)

Once the binding is completed, click the "OK" button to finish the binding process and
activate the RELOAD KIOSK machine service.

<img src="../Images/Installation/GDMC%20Reload%20Kiosk%20-%20Technician%20Instructions%20-%20IMG6.jpg" alt="Alt text" style="width: 70%;">

## Configure Kiosk

Select the GoldenDragon/MagicCity Logo on the screen.

<img src="../Images/Installation/GDMC%20Reload%20Kiosk%20-%20Technician%20Instructions%20-%20IMG7.jpg" alt="Alt text" style="width: 70%;">

Click the "LOGIN" button to access the login page.

<img src="../Images/Installation/GDMC%20Reload%20Kiosk%20-%20Technician%20Instructions%20-%20IMG8.jpg" alt="Alt text" style="width: 70%;">

Enter your registered account and password in the Mobile ID and Password fields, then click
the "LOGIN" button.

<img src="../Images/Installation/GDMC%20Reload%20Kiosk%20-%20Technician%20Instructions%20-%20IMG9.jpg" alt="Alt text" style="width: 70%;">

After logging in with a Store account, you can perform functions such as "SERVICE," "BILLS
LOG," "MANAGE," and "DEVICE SETTINGS."

<img src="../Images/Installation/GDMC%20Reload%20Kiosk%20-%20Technician%20Instructions%20-%20IMG10.jpg" alt="Alt text" style="width: 70%;">

---

### Service (Accounting Operation)

After logging in, press [SERVICE]. You will find Recycler and Stacker details on this page.

<img src="../Images/Installation/GDMC%20Reload%20Kiosk%20-%20Technician%20Instructions%20-%20IMG11.jpg" alt="Alt text" style="width: 70%;">


### Recycler 

Accept and dispense bills.

#### ADD: 

```
Start the BA to replenish banknotes, which can continuously be added.
```

<img src="../Images/Installation/GDMC%20Reload%20Kiosk%20-%20Technician%20Instructions%20-%20IMG12.jpg" alt="Alt text" style="width: 70%;">

#### BLEED: 
```
The banknotes output action, allowing the user to select the remaining
number of denomination banknotes to output. 

Operation to adjust denomination amount.
"-" (decrease) 
"+" (increase)
```

<img src="../Images/Installation/GDMC%20Reload%20Kiosk%20-%20Technician%20Instructions%20-%20IMG13.jpg" alt="Alt text" style="width: 70%;">

#### COMPLETE:
```
Displays the denomination information of the cash dispensed and
performs the cash dispensing action.
```

### Stacker 
Only stacks bills.

#### COLLECT: 

```
Transfer the banknotes from the Recycler cash box to the Stacker cash box.
After pressing the button, a confirmation transfer message will be displayed, press

CONFIRM to start action.

Wait for a longer period while the cash box processes the transfer.
The Recycler and Stacker management windows will appear, allowing cash handling based
on the information displayed.
After cash handling is completed, you can press MASTER CLEAR to clear the cash box
record information.
```

<img src="../Images/Installation/GDMC%20Reload%20Kiosk%20-%20Technician%20Instructions%20-%20IMG14.jpg" alt="Alt text" style="width: 70%;">

#### MASTER CLEAR: 
```
Clears the record information in the Stacker cash box.
```

<img src="../Images/Installation/GDMC%20Reload%20Kiosk%20-%20Technician%20Instructions%20-%20IMG15.jpg" alt="Alt text" style="width: 70%;">

---

### Bills Log & System Log

After logging in as an Agent or Distributor, click the BILLS LOG button on the Store
Operations page to navigate to the "LOG" page.

<img src="../Images/Installation/GDMC%20Reload%20Kiosk%20-%20Technician%20Instructions%20-%20IMG10.jpg" alt="Alt text" style="width: 70%;">

On the machine, you can view the records in the BILLS LOG and SYSTEM LOG.

##### BILLS LOG Record Description:

```
–ID: Transaction serial number.
–Date: Time of the transaction.
–Account: Account associated with the transaction.
–Operation: Type of operation.
–Amount: Currency value (US020/US005).
–To/From: Location where the cash is stored (recycler/Stacker).
–Bill Amount: Recorded quantity change of bills (US010: 1/US020: 7).
–BA Status: Status of bill acceptor for bill insertion.
–API Status: Transaction status.
–LOGO: Logo identifier (MC or GD).
```

<img src="../Images/Installation/GDMC%20Reload%20Kiosk%20-%20Technician%20Instructions%20-%20IMG16.jpg" alt="Alt text" style="width: 70%;">

##### SYSTEM LOG Record Description:
```
–DateTime: Time of the event.
–Level: Level of the event.
–ErrorCode: Error code associated with the event.
–Source: Source of the event.
–Message: Content of the event.
```

<img src="../Images/Installation/GDMC%20Reload%20Kiosk%20-%20Technician%20Instructions%20-%20IMG17.jpg" alt="Alt text" style="width: 70%;">

---

### Manage (System Setting)


After logging in as Store, Agent, or Distributor, click the MANAGE button on the Store
Operations page.

#### RESTART: 
```
Performs a restart of the POS machine.
```

#### SHUT DOWN: 
```
Shuts down the POS machine.

Please do not forcefully turn off the power during the shutdown process.
```

<img src="../Images/Installation/GDMC%20Reload%20Kiosk%20-%20Technician%20Instructions%20-%20IMG18.jpg" alt="Alt text" style="width: 70%;">

---

### Device Setting

After logging in as Store, Agent or Distributor, press [DEVICE SETTINGS] to access the
DEVICE SETTINGS page.

<img src="../Images/Installation/GDMC%20Reload%20Kiosk%20-%20Technician%20Instructions%20-%20IMG19.jpg" alt="Alt text" style="width: 70%;">

#### TICKET PRINTER TEST: 
```
Tests to see if the printer is functioning properly. 

A successful test printout indicates normal operation.
```
#### BILL VALIDATOR TEST:
```
Tests if the bill validator is functioning properly.
```
#### TICKET PRINTER: 
```
Accesses the PRINTER settings page.
```
#### DISABLE:
```
Disables the printer, ceasing its operation.
```
#### PHOENIX:
```
Switch the printer to "PHOENIX" and click [APPLY CHANGES] to complete the device switch.

Ensure correct wiring and switch settings for the printer.

Verify if the printer paper is properly loaded.

Return to the previous page and click the [TICKET PRINTER TEST] button to confirm if 
the printer can successfully print receipts.
```
#### PayCheck 4
```
Switch the printer to ""PayCheck 4"" and click [APPLY CHANGES] to

complete the device switch.

Ensure correct wiring and switch settings for the printer.

Verify if the printer paper is properly loaded.

Return to the previous page and click the [TICKET PRINTER TEST] button to confirm if
the printer can successfully print receipts.
```

#### BILL VALIDATOR:
```
Accesses the BILL VALIDATOR settings page.
```

#### ITL SMARTPayout:
```
Switch the BILL VALIDATOR to ""ITL SMARTPayout"" and click [APPLY CHANGES] to 
complete the device switch.

Ensure you’re wiring correct for the ITL SMARTPayout.

Return to the previous page and click the [BILL VALIDATOR TEST] button to confirm 
if the BILL VALIDATOR is functioning properly.
```


