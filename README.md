# DCB_prediction
Failures in Structures are common issues in the word composite materials 
When the composite material is produced the manufacturer can not guarantee the quality of the properties of the material because it is man-made, and this creates a deviation of + -15% to the amount of energy required to cause a fracture,
 it is a very important subject because there are a lot of accidents that happen because of Failures in Structures (Titanic, Challenger, etc), and getting a machine learning to understand what is the energy that leads to fracture can even save a life if it will be very accurate and make composite Structures safer to use and design.
we used machine learning models with given data about the layers of the material such as :
"UD:E_A",UD:E_T",UD:G_A",
" UD:G_T"," UD:nu_A"," UD:nu_T"," weave 0/90:E_{11} = E_{33}",
" weave 0/90:E_{22}"," weave 0/90:G_{13}",
" weave 0/90:G_{21} = G_{23}"," weave 0/90:nu_{13}"," weave 0/90:nu_{21} = nu_{23}",
" weave 45:E_{11} = E_{33}"," weave 45:E_{22}"," weave 45:G_{13}",
" weave 45:G_{21} = G_{23}"," weave 45:nu_{13}"," weave 45:nu_{21} = nu_{23}",
and the target value was the amount of energy it will take to break it (J-integral [N/m])
