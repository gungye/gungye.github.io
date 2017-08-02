Projection Matrix  
2 * near / (right - left)<pre>     </pre>(right+left) / (right - left)   0  
0                         2 * near / (top - bottom) (top + bottom) / (top - bottom) 0  
0                         0                         -(f+n) / (f-n)                  -2fn / (f-n)  
0                         0                         -1                              0  
  
right, left, top, bottom?  
right = -(width - px) * n / -fx  
left = px * n / -fx  
top = py * n / fy  
bottom = -(h-py)*n /fy  
  
Camera Matrix  
fx 0 px  
0 fy py  
0 0 0  
