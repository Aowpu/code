create table Khoa(
MaKhoa varchar(10) not null ,
Ten nvarchar(10),
DiaChi nvarchar(100)

)
create table Diem(
MaSV char(8) not null,
MaMon varchar(20) not null,
MaKy varchar(20) not null,
DiemTB float,
constraint CK_DiemTB check(DiemTB >=0 and DiemTB <=10)
) 
