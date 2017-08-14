# painful_files
fprintf(f,'%4.2f   %4.2f\n',[X Y]'); 

regression:
x - column-vector, vector of independant values;
xa - appended from a right side;
Mx=y;
Mxa=ya;
M=ya*xa'*(xa*xa')^-1;

об исследовании: 
(от интер до интра)
при 4-х без нормировки: 0.56 0.40 
с нормировкой 0.40 и 0.40
без нормировки при 6-ти: 0.61 и 0.2
при 8-ми: 0.61 0.13
без PCA: 0.52 0.57
