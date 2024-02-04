# DOUBLY REINFORCED BEAMS

Beams reinforced with steel both in tension and compression zones are called doubly reinforced beams. 

When concrete alone cannot generate the compressive force and compressive stresses sufficient to resist the given bending moment, the beams are strengthened by placing reinforcement in the compression zone. The reinforcement employed in the compression zone increases the beams' ductility. Structures in seismic zones are reinforced in compression. When compression reinforcement is applied in the beams, the long-term deflections in beams decrease.

## Conditions under which doubly Reinforced Beams are used. 
A doubly reinforced beam is generally provided under the following conditions:

- When the depth of beam is restricted due to headroom considerations, architectural or some other such reasons, eg, basement floors and staircases.

- When the Bending moment due to external loading is larger than limiting value of moment of resistance of a singly reinforced beam and the size of the beam is restricted (pre-determined).

- When the member is subjected to eccentric loading.

- When the beam is continuous over several supports, the section of the beam at the supports is usually designed as a doubly reinforced section.

The doubly reinforced beams are considered as uneconomical beams, as the strength of compression reinforcement is not fully utilized.
A rectangular section with reinforcement on tension and compression side is shown in below given Figure.

![Section Analysis](https://github.com/MaaninderSinghMatharu/MaaninderSinghMatharu/blob/main/stresstrain.jpg)

### Depth of neutral axis- ($x_u$)
   $$ x_u = \frac{0.87 f_y A_s_t - f_s_c A_s_c}{0.36 f_c_k b}$$
   
   where
    $f_y = $ characteristic strength of steel,
    $A_st = $ Area of steel in tension,
    $A_sc = $ Area of steel in compression,
    $f_ck = $ charactristic strentgh of concrete, and
    $b = $ width of the beam.
    
   Note$-$ Depth of neutral axis decreases with increase in compression steel.
   
### Moment of ultimate resistance- ($M_u$)
    
   $ M_u = 0.36 f_c_k b x_u (d-0.42 x_u) + f_s_c A_s_c (d-d')$

  where
   $d = $ effective depth of the beam,
   $f_sc = $ Stress in steel in compression,

### Area of steel-
  In tension-
     $$ A_st = \frac{M_u,lim}{0.87 f_y (d - 0.42 x_u_,_m_a_x)}$$
where

   $M_u,lim = $ limiting moment of resistance as shown in table below,
   ![limiting moment of resistance](https://github.com/MaaninderSinghMatharu/MaaninderSinghMatharu/blob/main/limiting%20moment%20of%20resistance.jpg)
   
   $ f_sc = $ Stress in steel in compression,
    
  In compression-
     $$ A_sc = \frac{M_u2}{f_sc (d - d')}$$


  Note$-$  of neutral axis decreases with increase in compression steel.

### Steps for design-
