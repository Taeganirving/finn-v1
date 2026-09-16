# Finn v1.0 Architecture

## 1. System Overview

### Purpose
Briefly describe how Finn will work as a complete system.

### Basic Flow
How does an interaction travel through Finn?

User Input → Processing → Response

---

## 2. System Diagram

Create a high-level diagram showing Finn's major components and how they communicate.

Questions to answer:
- What is at the center of Finn?
- What components provide input?
- What components provide output?
- How are the components connected?

---

## 3. Main Controller

### Purpose
What component will run Finn's software and control the hardware?

### Requirements
- What does the controller need to support?
- How many components must it control?
- What types of connections are required?

### Options Researched
- Option 1:
- Option 2:
- Option 3:

### Selected Solution
TBD

### Reasoning
Why was this option selected?

---

## 4. User Input System

### Purpose
How will the user intentionally interact with Finn?

### Requirements
- Must require intentional interaction
- Must be simple to use
- Must work without internet

### Options Researched
- Buttons
- Touch sensors
- Other:

### Selected Solution
TBD

### Interaction Ideas
What actions should different inputs trigger?

---

## 5. Face / Display System

### Purpose
How will Finn display his eyes and facial expressions?

### Requirements
- Display animated eyes
- Support multiple expressions
- Fit inside Finn's enclosure

### Options Researched
- Option 1:
- Option 2:
- Option 3:

### Selected Solution
TBD

### Expression Ideas
- Neutral
- Happy
- Annoyed
- Sleepy
- Excited
- Other:

---

## 6. Lighting System

### Purpose
How will Finn use lighting as part of his personality?

### Requirements
- TBD

### Options Researched
- TBD

### Selected Solution
TBD

### Lighting Behaviors
TBD

---

## 7. Sound System

### Purpose
How will Finn produce robotic sounds?

### Requirements
- TBD

### Options Researched
- TBD

### Selected Solution
TBD

### Sound Behaviors
TBD

---

## 8. Movement System

### Purpose
What part of Finn will move and how will movement contribute to expression?

### Requirements
- Limited expressive movement
- No autonomous navigation

### Mechanical Design
What physically moves?

### Options Researched
- TBD

### Selected Solution
TBD

### Movement Behaviors
TBD

---

## 9. Power System

### Purpose
How will Finn receive and distribute power?

### Requirements
- Rechargeable
- Portable
- Safely power all components

### Questions
- What battery type?
- What voltage is required?
- How will Finn charge?
- How will Finn turn on/off?
- How long should Finn operate per charge?

### Selected Solution
TBD

---

## 10. Software Architecture

### Purpose
How will Finn's software be organized?

### Main Responsibilities
- Detect user input
- Determine response
- Control face
- Control lights
- Control sound
- Control movement

### Behavior System
How should Finn decide which response to perform?

### States / Modes
Examples:
- Off
- Standby
- Active
- Responding
- Sleep

Final states:
TBD

---

## 11. Internal Communication

Determine how Finn's components communicate with the main controller.

### Connections
| Component | Connection Type | Controller Interface |
|---|---|---|
| Face | TBD | TBD |
| Lights | TBD | TBD |
| Sound | TBD | TBD |
| Movement | TBD | TBD |
| User Input | TBD | TBD |

---

## 12. Physical Layout

Plan where the major components will physically sit inside Finn.

Consider:
- Display placement
- Controller placement
- Speaker placement
- Battery placement
- Movement mechanism
- Buttons / touch sensors
- Charging port
- Power switch
- Wiring
- Access for repairs
- Heat / ventilation

### Rough Dimensions
TBD

### Internal Layout
TBD

---

## 13. Safety and Reliability

Consider:
- Battery safety
- Charging safety
- Moving parts
- Heat
- Wiring
- Component protection
- Safe shutdown
- Enclosure durability

Decisions:
TBD

---

## 14. Final Architecture

Complete this section after research.

### Controller
TBD

### Display
TBD

### Input
TBD

### Lighting
TBD

### Sound
TBD

### Movement
TBD

### Battery / Power
TBD

### Software Approach
TBD

---

## 15. Open Questions

Track unresolved architecture decisions here.

- [ ] Main controller?
- [ ] Display?
- [ ] User input method?
- [ ] Lighting?
- [ ] Sound hardware?
- [ ] Movement mechanism?
- [ ] Battery?
- [ ] Charging system?
- [ ] Physical dimensions?
- [ ] Software structure?