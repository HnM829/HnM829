program bai5;
uses crt;
var a:array[1..99]of integer;
    i,n,t,x,y:integer;
begin
clrscr;
write('nhap x= ');
readln(x);
write('nhap y(y>=x)= ');
readln(y);
write('nhap n=');
readln(n);
t:=0;
for i:=1 to n do 
 begin 
  if ( i mod 4 = 0 ) and (i>=x) and (i<=y) then
   begin
    t:=t+i;
   end;
  end;
writeln('tong cac so thoa man la',t);
readln
end.
