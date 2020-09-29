# p8105_HW2_rkm2147

this is the project for the second hw and following the lecture

relocate(prez_gop,prez_dem) %>% 
  pivot_longer(
    prez_gop:prez_dem,
    names_to = "president",
    values_to = "amount"
  )
  
  unsure if this code is going to work
  