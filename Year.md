var humanYearsCatYearsDogYears = function(humanYears) {
  let mass = [];
   mass.push(humanYears);
  for( let i = 1 ; i<=humanYears ; i++)
    {
      if(i===1)
        {
          mass.push(15);
          mass.push(15);
        }
      else if(i===2)
        {
          mass[1]=mass[1]+9;
          mass[2]=mass[2]+9;
        }
      else if(i>=3)
        {
          mass[1]=mass[1]+4;
          mass[2]=mass[2]+5;
        }
    }
  return mass;
    
}