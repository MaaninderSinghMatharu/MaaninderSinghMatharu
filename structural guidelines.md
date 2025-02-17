# **IS 13920:2016**

**CLAUSE 5: GENERAL SPECIFICATIONS**  

---

### **5.1 Compliance with Standards**  
The design and construction of reinforced concrete buildings shall conform to **IS 456**, except as modified by the provisions of this standard for members participating in lateral force resistance.  

---

### **5.2 Minimum Concrete Grade**  
The minimum grade of structural concrete shall be:  
- **M20** for general use.  
- **M25** for buildings:  
  - Exceeding **15 m in height** in **Seismic Zones III, IV, or V**;  
  - Not less than the grade required by **IS 456** based on exposure conditions.  

---

### **5.3 Steel Reinforcement Requirements**  
Steel reinforcement resisting earthquake-induced forces in **RC frame members** and **boundary elements of structural walls** shall comply with the following:  

#### **5.3.1 Material Properties**  
Reinforcement shall meet all of the following criteria:  
- **Elongation**: Minimum **14.5%**.  
- **Strength Ratios**:  
  - Ratio of ultimate tensile stress to 0.2% proof stress: **≥1.15** and **≤1.25**.  
- **Grades**:  
  - Steel bars with **minimum 0.2% proof stress** of **415 MPa**, **500 MPa**, or **550 MPa**, conforming to **IS 1786**.  

#### **5.3.2 Proof Stress Limitation**  
The actual **0.2% proof stress** of steel bars, determined by tensile testing, shall not exceed the **characteristic 0.2% proof stress** by more than **20%**.  

---

### **5.4 Lintel and Plinth Beams**  
- **Lintel beams** shall preferably **not** be integrated into columns to avoid short-column effects. If integrated, they shall be included in the analytical model.  
- **Plinth beams**, **staircase beams**, and **slabs** framing into columns shall be included in the analytical model for structural analysis.  

---

### **5.5 Regularity in Moment-Resisting Frames**  
- **RC regular moment-resisting frame buildings** shall have planar frames oriented along the **two principal plan directions** of the building.  
- **Irregularities** listed in **Tables 5 or 6 of IS 1893 (Part 1)** shall be avoided. Buildings with such irregularities, **floating columns**, or **set-back columns** are prone to poor seismic performance.  
- If irregularities are unavoidable, **nonlinear dynamic analyses** shall demonstrate that the structure poses no threat to life or property.   

--- 

**7 COLUMNS AND INCLINED MEMBERS**

**7.1 Geometry**  
Requirements of this section shall apply to columns and inclined members resisting earthquake-induced effects, in which the factored axial compressive stress due to gravity and earthquake effects exceeds **$0.08 f_{ck}$**. The factored axial compressive stress considering all load combinations involving seismic loads shall be limited to **$0.40 f_{ck}$** in all such members, except in those covered in Clause 11.

For columns of shapes other than rectangular and circular (such as “T”, “X”, or “+” shaped), which form part of the lateral load resisting system, appropriate designs and detailing shall be carried out using specialist literature.

**7.1.1** The minimum dimension of a column shall not be less than:  
- **$20 d_b$**, where $d_b$ is the diameter of the largest longitudinal reinforcement bar in the beam passing through or anchoring into the column at the joint; or  
- **300 mm** (see Fig. 7).

**7.1.2** The cross-sectional aspect ratio (ratio of smaller dimension to larger dimension) shall not exceed **0.4**.

**7.2 Longitudinal Reinforcement**  
**7.2.1 Minimum and Maximum Reinforcement**  
- The minimum area of longitudinal reinforcement shall be **0.8%** of the gross cross-sectional area of the column.  
- The maximum area of longitudinal reinforcement shall not exceed **6%** of the gross cross-sectional area.

**7.2.2 Spacing of Longitudinal Bars**  
The clear spacing between longitudinal bars shall not exceed **300 mm**.

**7.2.3 Splices**  
**7.2.3.1 Lap Splices**  
- Lap splices shall be confined by closed links over the entire splice length, spaced at ≤ **100 mm**.  
- Lap length shall not be less than the **development length in tension** for the largest bar.  
- Splices shall not be located:  
  (a) Within joints;  
  (b) Within **$2d$** from the beam face; or  
  (c) Where yielding is likely.  
- Not more than **50%** of bars shall be spliced at any section.

**7.2.3.2 Mechanical Couplers**  
- Only couplers conforming to **IS 16172** and capable of developing **125%** of the bar’s yield strength shall be used.  
- Not more than **50%** of bars shall be coupled at any section, with adjacent couplers staggered by ≥ **300 mm**.

**7.2.3.3 Welded Splices**  
- Welded splices are prohibited in regions prone to yielding.

**7.3 Transverse Reinforcement**  
**7.3.1 Type and Detailing**  
- Transverse reinforcement shall consist of **closed loops** (rectangular or spiral) with **135° hooks** and an extension of **8 times bar diameter** (≥ 75 mm).  
- In rectangular columns, cross-ties shall be added if any side exceeds **300 mm** (see Fig. 10).

**7.3.2 Spacing and Diameter**  
- Minimum diameter: **8 mm** (for longitudinal bars ≤ 32 mm) or **10 mm** (for bars > 32 mm).  
- Maximum spacing:  
  (a) **Half the least lateral dimension** of the column;  
  (b) **6 times** the smallest longitudinal bar diameter; or  
  (c) **100 mm** (in regions with special confining reinforcement).

**7.4 Design Shear Force in Columns**  
The design shear force demand ($V_u$) shall be the larger of:  
1. Factored shear force from linear analysis;  
2. Equilibrium shear due to plastic hinges in beams:  
$$
V_u = 1.4 \left( \frac{M_u^{Ah} + M_u^{Bs}}{h_{st}} \right)
$$  
where $M_u^{Ah}$ and $M_u^{Bs}$ are beam moments at column faces, and $h_{st}$ is storey height.

**7.5 Shear Strength Calculation**  
Shear strength shall be computed as per **IS 456**, excluding contributions from bent-up bars or inclined links.

**7.6 Special Confining Reinforcement**  
**7.6.1 Application**  
Special confining reinforcement shall be provided:  
- Over a length $l_o \geq \text{max}(D, \frac{1}{6} \text{clear height}, 450 \text{ mm})$ at column ends.  
- Where the point of contra-flexure lies outside the middle half of the column.

**7.6.2 Spacing and Area**  
- Spacing of confining links ≤ **100 mm**.  
- Area of cross-section ($A_{sh}$) for rectangular links:  
$$
A_{sh} = \text{max} \left[ 0.18 s_v h \frac{f_{ck}}{f_y} \left( \frac{A_g}{A_k} - 1 \right), \quad 0.05 s_v h \frac{f_{ck}}{f_y} \right]
$$  
where $h \leq 300 \text{ mm}$, $A_g$ = gross area, and $A_k$ = core area.

**7.6.3 Termination in Footings**  
Special confining reinforcement shall extend ≥ **300 mm** into footings or mats (see Fig. 13).

**7.6.4 Columns Supporting Discontinued Members**  
Full-height confining reinforcement is required for columns supporting discontinued stiff members (e.g., walls).

---  
*Note: Figures referenced (e.g., Fig. 7, 10, 13) are to be included as per the original standard.*


### **11 GRAVITY COLUMNS IN BUILDINGS**

Gravity columns in buildings shall be **designed** according to the provisions of **11.1** and **11.2** to resist bending moments and shear forces induced when subjected to **$R$** times the design lateral displacement under the factored equivalent static design seismic loads as specified in **IS 1893 (Part 1)**.

#### **11.1 General Requirements**

The provisions in **11.1.1** and **11.1.2** shall be satisfied when the induced bending moments and horizontal shear forces under the said lateral displacement, combined with factored gravity bending moments and shear forces, do not exceed the design moment of resistance and design lateral shear capacity of the column.

##### **11.1.1 Reinforcement Requirements**
Gravity columns shall satisfy the following:
- **Longitudinal Reinforcement:** As per **Clause 7.3.2**.
- **Transverse Reinforcement:** As per **Clause 7.4.1** and **7.4.2**.
- **Spacing of Links:** The spacing of links along the full column height shall not exceed **6 times the diameter of the smallest longitudinal bar** or **150 mm**, whichever is smaller.

##### **11.1.2 Columns with High Axial Stress**
For gravity columns with factored gravity axial stress exceeding **$0.4 f_{ck}$**, the following additional requirements shall be met:
- The transverse reinforcement shall be at least **one-half** of the special confining reinforcement required by **Clause 7.6**.

#### **11.2 Special Requirements for Columns Exceeding Design Capacity**

When the induced bending moments and shear forces under the said lateral displacement, combined with factored gravity bending moments and shear forces, exceed the design moment and shear strength of the frame, the following provisions shall be satisfied:

##### **11.2.1 Mechanical and Welded Splices**
- Mechanical and welded splices shall comply with the requirements of **Clause 7.3.2.2** and **7.3.2.3**.
- At any section, not more than **50 percent** of the bars shall be coupled, and the next location of couplers shall be at least **300 mm** away.

##### **11.2.2 Transverse Reinforcement**
- Gravity columns shall satisfy the transverse reinforcement requirements of **Clause 7.4** and the special confining reinforcement requirements of **Clause 7.6**.

---  
*Note: Figures referenced (e.g., Fig. 7, 10, 13) are to be included as per the original standard.*