# System Design Practice Questions — Organized Study Notes (Chapter 5) 📘

---

## 1. Processes contain the business logic, also called business rules, which transforms the data and produces the required results

**Type:** True/False (5 Points)

- A. True
- B. False

✅ **Right Answer:** A

---

## 2. In a data flow diagram (DFD), a process symbol can have only one outgoing data flow

**Type:** True/False (5 Points)

- A. True
- B. False

✅ **Right Answer:** B

---

## 3. In a data flow diagram (DFD), systems analysts call an entity that receives data from the system a source

**Type:** True/False (5 Points)

- A. True
- B. False

✅ **Right Answer:** B

---

## 4. What makes one system more complex than another is the number of components, the number of levels, and the degree of interaction among its processes, entities, data stores, and data flows

**Type:** True/False (5 Points)

- A. True
- B. False

✅ **Right Answer:** A

---

## 5. When a data flow diagram (DFD) is exploded, the higher-level diagram is called the child diagram

**Type:** True/False (5 Points)

- A. True
- B. False

✅ **Right Answer:** B

---

# Multiple Choice Questions

---

## 6. A data flow diagram (DFD) shows **\_**

**Type:** Multiple-Choice (5 Points)

- A. how data are related
- B. what key fields are stored in the system
- C. how a system transforms input data into useful information
- D. what data is stored in the system

✅ **Right Answer:** C

---

## 7. In addition to the Gane and Sarson symbol set, another popular symbol set is the **\_** symbol set

**Type:** Multiple-Choice (5 Points)

- A. Mantissa
- B. Jira
- C. Zachman
- D. Yourdon

✅ **Right Answer:** D

---

## 8. By showing processes as **\_**, an analyst can create data flow diagrams (DFDs) that show how the system functions but avoid unnecessary detail and clutter

**Type:** Multiple-Choice (5 Points)

- A. black boxes
- B. process descriptions
- C. business rules
- D. decision tables

✅ **Right Answer:** A

---

## 9. In a data flow diagram (DFD), the Gane and Sarson symbol for a data flow is a **\_**

**Type:** Multiple-Choice (5 Points)

- A. segment of a differentiable curve
- B. line with a single or double arrowhead
- C. flat rectangle that is open on the right side and closed on the left side
- D. triangle, which may be shaded to make it look three-dimensional

✅ **Right Answer:** B

---

## 10. In a data flow diagram (DFD), a black hole is a process that has **\_**

**Type:** Multiple-Choice (5 Points)

- A. no input
- B. at least one output and one input, but the output obviously is insufficient to generate the input shown
- C. no output
- D. at least one input and one output, but the input obviously is insufficient to generate the output shown

✅ **Right Answer:** C

---

## 11. A **\_** is logically impossible in a data flow diagram (DFD) because a process must act on input, shown by an incoming data flow, and produce output, represented by an outgoing data flow

**Type:** Multiple-Choice (5 Points)

- A. spontaneous combustion
- B. gray matter
- C. black hole
- D. server farm

✅ **Right Answer:** C

---

## 12. If processes must be performed in a specific sequence, the information should be documented in the **\_**

**Type:** Multiple-Choice (5 Points)

- A. leveling guide
- B. process descriptions
- C. data dictionary
- D. data flow diagram (DFD)

✅ **Right Answer:** B

---

## 13. **\_** is the process of drawing a series of increasingly detailed data flow diagrams (DFDs), until all functional primitives are identified

**Type:** Multiple-Choice (5 Points)

- A. Leveling
- B. Balancing
- C. Indexing
- D. Looping

✅ **Right Answer:** A

---

## 14. Balancing **\_**

**Type:** Multiple-Choice (5 Points)

- A. uses a series of increasingly detailed data flow diagrams (DFDs) to describe an information system
- B. ensures that the input and output data flows of the parent data flow diagram (DFD) are maintained on the child data flow diagram (DFD)
- C. uses a series of increasingly sketchy data flow diagrams (DFDs) to describe an information system
- D. ensures that the input and output data flows of the child data flow diagram (DFD) are maintained on the parent data flow diagram (DFD)

✅ **Right Answer:** B

---

## 15. In a data dictionary, a(n) **\_** is the smallest piece of data that has meaning within an information system

**Type:** Multiple-Choice (5 Points)

- A. field
- B. index
- C. record
- D. pixel

✅ **Right Answer:** A

---

## 16. The data dictionary usually records and describes a default value, which is the **\_**

**Type:** Multiple-Choice (5 Points)

- A. set of values permitted for the data element
- B. identification of the user(s) responsible for changing values for the data element
- C. specification for the origination point for the data element’s value
- D. value for the data element if a value otherwise is not entered for it

✅ **Right Answer:** D

---

## 17. In a data dictionary, **\_** is the maximum number of characters for an alphabetic or character data element or the maximum number of digits and number of decimal positions for a numeric data element

**Type:** Multiple-Choice (5 Points)

- A. domain
- B. valence
- C. length
- D. index

✅ **Right Answer:** C

---

## 18. In a data dictionary, some data elements have **\_** rules. For example, an employee’s salary must be within the range defined for the employee’s job classification

**Type:** Multiple-Choice (5 Points)

- A. domain
- B. range
- C. validity
- D. mastered

✅ **Right Answer:** C

---

## 19. **\_** is based on combinations of the three logical structures, or control structures, which serve as building blocks for the process

**Type:** Multiple-Choice (5 Points)

- A. Modular design
- B. Interface design
- C. Visual design
- D. Product design

✅ **Right Answer:** A

---

## 20. Many analysts follow **\_**, which means that they develop a physical model of the current system, a logical model of the current system, a logical model of the new system, and a physical model of the new system

**Type:** Multiple-Choice (5 Points)

- A. a four-model approach
- B. a process description
- C. the Zachman Framework
- D. the Gane and Sarson symbol

✅ **Right Answer:** A

---

# Quick Review Summary ✨

| Topic               | Key Concept                                                 |
| ------------------- | ----------------------------------------------------------- |
| DFD                 | Shows how data moves and is transformed                     |
| Leveling            | Creating increasingly detailed DFDs                         |
| Balancing           | Maintaining same input/output between parent and child DFDs |
| Black Hole          | Process with no output                                      |
| Data Dictionary     | Stores definitions and details about data elements          |
| Modular Design      | Built using logical/control structures                      |
| Four-Model Approach | Current + New system logical/physical models                |
