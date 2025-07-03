## Tasks Implemented

### **Task 1: Basic Circuit Board**

- **Drag and Drop Support**
  - Users can drag gates (e.g., H, CG) from the Operators panel onto the Circuit board.
- **Gate Placement**
  - Gates can be placed on any qubit line in any column.
- **Visual Rendering**
  - Each qubit line displays gates aligned horizontally in columns.

---

### **Task 2: Support Gates of Varying Width**

- **Gate Expansion**
  - Custom gates (e.g. CG) can expand to span multiple columns when required.
- **Overlap Prevention**
  - Ensures expanded gates do not overlap existing gates on any qubit line.
- **Column Integrity**
  - Gates spanning multiple columns effectively occupy only one gate slot per column across all qubits.
- **User Feedback**
  - Alerts the user if expansion is invalid due to overlap:
  

Note: `node_modules` and `.next` folders have been removed to reduce the repository size below 25 MB. Install dependencies after cloning.

## Installation

1. Clone the repository:

```bash
git clone <repository-url>
cd <repository-folder>
npm install
npm run dev
