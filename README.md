# NANDcraft: The Universal Gate Workshop

An interactive, browser-based educational playground designed to help students master NAND gate universality, circuit synthesis, and Boolean logic equivalence.

Built with vanilla HTML5, CSS3, and SVG—zero external build tools or framework dependencies required.

---

## ⚡ How It Works

The objective is to synthesize target digital logic circuits using **only 2-input NAND gates**. Connect input signal rails to gate pins, observe live voltage propagation, and verify circuit equivalence against dynamic truth tables in real time.

### Key Modes
* **Basics:** Recreate core textbook logic gates (NOT, AND, OR, NOR, XOR, XNOR) starting from a clean slate.
* **Advanced:** Build multi-gate, 3-wire composite circuits (2-to-1 Multiplexer, 3-Input Majority Voter, Parity bit generator, and Sum of Products logic).
* **Truth Table Drill:** Test theoretical comprehension by filling in missing values (`0`, `1`, `?`) for pre-wired schematic configurations.
* **Sandbox & Custom Equation Parser:** Add up to 5 NAND gates freely, experiment with custom topologies, or input arbitrary Boolean algebraic equations (e.g., `A'B + AB'`, `(A + B)'`) to auto-generate a target truth table to solve against.

---

## 🛠️ Controls & Features

* **Wiring:** Click/tap an input rail (`A`, `B`, `C/S`) or NAND output, then click/tap any gate input pin. Drag-and-drop wiring with magnetic snapping (25px threshold) is also fully supported.
* **Disconnect:** Click any occupied input terminal or active wire line to sever the connection.
* **Signal Tracing:** Live high-voltage states (`1`) pulse neon emerald; low-voltage states (`0`) render slate gray. Toggling input rails cascades voltage through the entire circuit instantly.
* **Verification:** Side-by-side truth tables validate states live, highlighting matching rows and triggering completion chimes when equivalence is achieved.
* **Textbook Walkthroughs:** A non-intrusive hint system provides De Morgan algebraic clues and complete step-by-step schematic solutions if you get stuck.

---

## 🚀 Running Locally

No installation or server setup is necessary. Simply clone the repository and open `index.html` in any modern web browser:

```bash
git clone [https://github.com/](https://github.com/)<your-username>/<repo-name>.git
cd <repo-name>
open index.html
