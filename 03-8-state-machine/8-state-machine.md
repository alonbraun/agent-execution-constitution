# The 8-State Execution Machine

Execution is modeled as a state machine.
Only one state may be active at any time.

---

## 1. Sensing
**Intent:** Detect signals without interpretation  
**Output:** Signal Set  
**Exit:** Signals collected

---

## 2. Expressing
**Intent:** Articulate vision and intent  
**Interface:** Human clarification layer (if required)  
**Output:** Vision Draft  
**Exit:** Vision declared

---

## 3. Reorient
**Intent:** Synchronize agent models  
**Outputs:**
- Shared definitions
- Authority Map
- Interface contracts  
**Exit:** Model convergence

---

## 4. Plan
**Intent:** Design execution approach  
**Outputs:**
- Selected plan
- Method routing
- Rejected alternatives  
**Exit:** Plan committed

---

## 5. Develop
**Intent:** Build capability  
**Output:** Functional system or artifact  
**Exit:** Build complete

---

## 6. Function
**Intent:** Validate reliability  
**Output:** Validation results  
**Exit:** Core function verified

---

## 7. Engage
**Intent:** Interact with the real world  
**Output:** External signals  
**Exit:** Feedback stream active

---

## 8. Feedback
**Intent:** Integrate learning  
**Output:** Decision to iterate, pivot, or stop  
**Exit:** Next-state decision recorded

---

## Loop Rule

If feedback contradicts the declared vision,
the human clarification interface may reopen.
