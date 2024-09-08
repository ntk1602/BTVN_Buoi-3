đối với for (int i = 0; i <= index; i++) khi vòng lặp 
kết thúc, temp sẽ trỏ đến node có chỉ số = index vì vòng 
lặp thực hiện đúng index lần

vd bun cha, com tam, banh mi, hu tieu
for(int i = 0; i <= 2; i++)
lan 1: i=0, temp tro den bun cha
lan 2: i=1, temp tro den com tam
lan 3: i=2, temp tro den banh mi
lan 4: i=3, vi co dieu kien i<=2 nen vong lap ket thuc



đối với for (int i = 0; i < index; i++) khi vòng lặp kết thúc,
temp sẽ trỏ đến node có chỉ số ngay trước index vì vòng lặp 
chỉ thực hiện index-1 lần nên temp chỉ được dịch chuyển index-1 bước

vd bun cha, com tam, banh mi, hu tieu
for(int i = 0; i < 2; i++)
lan 1: i=0, temp tro den bun cha
lan 2: i=1, temp tro den com tam
lan 3: i=2, vi dieu kien i<2 nen vong lap ket thuc