---
pdf: true
level: confidential
---


# Configuration and Diagnostics

For a complete installation diagnostic, use our smart app, available at both PlayStore and AppStore.

## LEDs

The in-built RGB LED for diagnosis is a visual indicator to inform about the operational status or health of the system. These LEDs are designed to emit different colours or patterns to communicate specific messages, providing users or technicians with a quick and intuitive way to assess the condition of the device. See the below description to identify the system status through the status LED.

The receiver will always blink **4 times** in a row. Each blink has a different meaning:

![Receiver](images/receiver_leds.png){ width="300px"}

### 1st Blink - RF Status
|**Color** | **Description**                        |
|---------|---------------------------|
| <span style="color:red">RED</span> | Channels 1 and 2 not receiving frames |
| <span style="color:green">GREEN</span>  | Channel 1 or 2 receiving frames |
| <span style="color:blue">BLUE</span>  | Channels 1 and 2 receiving frames  |

### 2nd Blink - 2.4GHz Link Status
|**Color** | **Description**                        |
|---------|---------------------------|
| <span style="color:red">RED</span> | Advertising only |
| <span style="color:green">GREEN</span>  | Advertising and scanning |
| <span style="color:blue">BLUE</span>  | Connected  |

### 3rd Blink - CAN/UART Status
|**Color** | **Description**                        |
|---------|---------------------------|
| <span style="color:red">RED</span> | CAN/UART self-diagnostic failed |
| <span style="color:green">GREEN</span>  | CAN/UART working, but no data received |
| <span style="color:blue">BLUE</span>  | CAN/UART working and data has been received  |

### 4th Blink - General
|**Color** | **Description**                        |
|---------|---------------------------|
| <span style="color:red">RED</span> | Always RED |