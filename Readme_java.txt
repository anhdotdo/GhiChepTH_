Ghi chep kien thuc can nho:

Chu de: Access modifier
1. private: pham vi trong class (trong cung 1 class)
2. default: pham vi trong class, package
3. protected: pham vi trong class, package, khac package nhung phai ke thua
4. puclic: pham vi trong class, package, ngoai package

Chu de: Cac dac tinh huong doi tuong (OOP)
1. dong goi ( encapsulation )
Dam bao tinh bao mat, tinh toan ven cua doi duong bang cach ngan chan truy cap truc tiep cung nhu
truy cap tu ben ngoai lam thay doi cac thuoc tinh
2. ke thua (inheritance)
Dam bao phat trien phan mem thong qua viec ke thua lop cu va phat trien nhung tinh nang moi
3. truu tuong ( abstraction)
Dam bao tap trung vao cot loi cua doi tuong ma khong ban tam no hoat dong ntn bang cach cung cap 
tinh nang phia nguoi dung, nhung khai niem ma bo qua chi tiet trien khai ben trong
4. da hinh ( polymorphism)
Tinh da hinh ton tai song song voi tinh ke thua. Tinh ke thua duoc hieu la co nhieu lop con ke thua 
tu 1 lop cha va co nhieu tinh nang khac nhau; cung 1 phuong thuc duoc thuc hien bang
nhieu cach khac nhau

Chu de: Bien 
co 3 loai: local variable, instance variable, static variable
1. LOCAL VAR: 
a. la gi: ben trong phuong thuc (tuong duong phuong thuc)
b. vong doi: cung voi phuong thuc (tuong duong phuong thuc)
c. cach truy cap: N/A (binh thuong), khong duoc dung Access Modifier
d. bo nho luu truu: stack
e. gia tri khoi tao ban dau: can khoi tao
2. INSTANCE VAR:
a. la gi: ben ngoai phuong thuc (tuong duong phuong thuc)
b. vong doi: cung voi object
c. cach truy cap: thong qua object, TH dac biet dung ten truc tiep
d. bo nho luu truu: heap
e. gia tri khoi tao ban dau: default
3. STATIC VAR: 
a. la gi: tu khoa "static", ben ngoai phuong thuc (tuong duong phuong thuc)
b. vong doi: cung voi chuong trinh
c. cach truy cap: thong qua ten class, TH dac biet dung ten truc tiep
d. bo nho luu truu: private static
e. gia tri khoi tao ban dau: default

Chu de: This - key word
1. tham chieu toi bien instance cua lop hien tai
2. this() tham chieu den constructor cua lop hien tai
3. this dung de tra ve instance cua lop hien tai

Chu de: set() va get() trong java
1. Neu class co thuoc tinh nguyen thuy (in, float...), ham set() va get() dung nhu thuong
2. Neu class co thuoc tinh co kieu du lieu tham chieu (mang, kieu class), ham set() va get()
phai dung phuong thuc clone(). 
2a: Nguyen nhan: co su anh xa giua thuoc tinh voi o nho cua tham so truyen vao
2b: Giai phap: tao vung nho moi va copy gia tri tham so vao, sau do gan cho thuoc tinh
3. TH thuoc tinh la kieu tham chieu String, nhung ban chat bien String thay doi thi tao ra vung nho moi

Chu de: Overloading va overridding trong java
1. Overloading: la nap chong, la co nhieu phuong thuc cung ten trong cung 1 class nhung ma khac tham so
2. overridding: la ghi de, lop con viet lai phuong thuc cua lop cha, tu khoa this de chong ghi de
doi voi lop con

Chu de: Thuoc tinh truu tuong (abstraction)
1. Lop ke thua: dung tu khoa abstract truoc class, chi tao duoc object tu lop con ke thua tu 
lop truu tuong do
2. Phuong thuc ke thua: dung tu khoa abstract (vd: public abstract Object clone();), chi khai bao
chu khong dinh nghia phuong thuc ke thua trong lop cha, phai overridding phung thuc do trong 
lop con ke thua

Chu de: Interface
1. la gi: tu khoa Interface, ten coi chu cai dau "I", 
mac dinh: thuoc tinh co dang "puclic static final"
mac dinh: phuong thuc co dang "public abstract"
2. Cach dung: lop con "ke thua" Interface thi cung ke thua cac phuong thuc cua Interface

Che de: Try catch & throw & finally
1. try ... catch:
xac dinh 1 doan code co the xay ra loi de xu ly (vd: in ra thong bao)
cu phap: 
try{
    //doan code
}catch(Exception e){
    //xy ly
}
2. thow:
nem loi ra de thong bao 
Cu phap:
thow new ten_class("thong_bao")
3. finally:
dung sau try ... catch