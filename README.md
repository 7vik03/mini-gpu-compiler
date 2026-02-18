# mini-gpu-compiler


A compiler for mini-gpu. Converts C-like kernel code to GPU assembly/binary.

> **Note:** This will be developed after mini-gpu v1.0 is complete with working assembler. The assembler is the v1 approach. This compiler is v2.

## Components

### Frontend
- [ ] **Lexer** — Tokenize source code
- [ ] **Parser** — Build AST from tokens
- [ ] **Semantic Analysis** — Type checking, symbol resolution

### Intermediate Representation
- [ ] **IR Generation** — Convert AST to IR
- [ ] **IR Optimizer** — Dead code elimination, constant folding
- [ ] **SSA Form** — Static single assignment (optional)

### Backend
- [ ] **Instruction Selection** — Map IR to mini-gpu instructions
- [ ] **Register Allocation** — Assign variables to registers
- [ ] **Code Generation** — Emit assembly or binary

### Optimizations
- [ ] **Constant Folding** — Evaluate constants at compile time
- [ ] **Dead Code Elimination** — Remove unused code
- [ ] **Common Subexpression Elimination** — Reuse computed values
- [ ] **Loop Unrolling** — Unroll small loops (optional)
