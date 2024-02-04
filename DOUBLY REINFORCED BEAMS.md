## DOUBLY REINFORCED BEAMS
### 1 Assumptions

38. Design for the limit state of collapse in flexure shall
be based on the assumptions given below:

    1. Plane sections normal to the axis remain plane after bending.
    1. The maximum strain in concrete at the outermost compression fibre is taken as 0.0035 (0.35%) in bending.
    1.  The relationship between the compressive stress distribution in concrete and the strain in concrete may be assumed to be
        - rectangle,
        - trapezoid,
        - parabola or
        - any other shape which results in prediction of strength in substantial agreement with the results of test.
    
    An acceptable stress-strain curve is given in Fig. 21 of IS code. The actual strength of concrete in a structural element, such as a beam and column, is different from the cube strength. This difference is attributed to various factors, including the effects of confinement, size effect, and stress distribution in the structural element. Due to this fact, for the design purposes, the compressive strength of concrete in the structure shall be assumed to be 0.67 times the characteristic strength. The partial safety factor $\gamma_m = 1.5$ shall be applied in addition to this.

    Note$-$ For the stress-strain curve in Fig. 21 the design stress block parameters are as follows (see Fig. 22):
    
    Area of stress block $ = 0.36 f_{ck} \times x_u$
    
    Depth of centre of compressive force from the extreme fibre in compression $ = 0.42 x_u$

    where

    \begin{align*}
    f_{ck} &= \begin{aligned}[t] 
                    &\text{characteristic compressive strength} \\
                    &\text{of concrete, and}
               \end{aligned} \\
    x_u &= \begin{aligned}[t] 
                    &\text{depth of neutral axis.}
               \end{aligned}
    \end{align*}

    - The tensile strength of the concrete is ignored.
    - The stresses in the reinforcement are derived from representative stress-strain curve for the type of steel used. Typical curves are given in Fig. 23. For design purposes the partial safety factor $\gamma_m$ , equal to 1.15 shall be applied.
    - The maximum strain in the tension reinforcement in the section at failure shall not be less than: $$ \frac{f_y}{1.15 E_s} + 0.002$$

    where

    $f_y = $ characteristic strength of steel, and

    $E_s = $ modulus of elasticity of steel.

    
![Starin and Stress Distribution for RC Beam](BeamStrainStress.svg)
    

## DOUBLY REINFORCED BEAMS

Beams reinforced with steel both in tension and compression zones are called doubly reinforced beams. 

When concrete alone cannot generate the compressive force and compressive stresses sufficient to resist the given bending moment, the beams are strengthened by placing reinforcement in the compression zone. The reinforcement employed in the compression zone increases the beams' ductility. Structures in seismic zones are reinforced in compression. When compression reinforcement is applied in the beams, the long-term deflections in beams decrease.

### Conditions under which doubly Reinforced Beams are used. 
A doubly reinforced beam is generally provided under the following conditions:

- When the depth of beam is restricted due to headroom considerations, architectural or some other such reasons, eg, basement floors and staircases.

- When the Bending moment due to external loading is larger than limiting value of moment of resistance of a singly reinforced beam and the size of the beam is restricted (pre-determined).

- When the member is subjected to eccentric loading.

- When the beam is continuous over several supports, the section of the beam at the supports is usually designed as a doubly reinforced section.

The doubly reinforced beams are considered as uneconomical beams, as the strength of compression reinforcement is not fully utilized.
A rectangular section with reinforcement on tension and compression side is shown in below given Figure.

![Section Analysis](file:///C:/Users/Daybie/Downloads/stresstrain.jpg)

#### Depth of neutral axis-
     $$ \frac{0.87 f_y A_st - f_sc A_sc}{0.36 f_ck b}