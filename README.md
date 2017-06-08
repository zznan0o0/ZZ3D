###3d => 2d //上下相反
scale 公式 fallLength/(fallLength+z)
X = scale * x
Y = scale * y

###rotateX
y1 = y * cos - z * sin;
z1 = z * cos + y * sin;

###rotateY
x1 = x * cos - z * sin;
z1 = z * cos + x * sin;

###rotateZ
x1 = x * cos - y * sin
y1 = x * sin + y * cos

###球面公式
x=r*sinθ*cosΦ  
y=r*sinθ*sinΦ   
z=r*cosθ;
//均匀分布公式（看不懂）
θ = arccos( ((2*num)-1)/all - 1);
Φ = θ*sqrt(all * π);