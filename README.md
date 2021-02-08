# Larihan2-PemrogramanMobile2
Array

void main(){
  
  var data=[];
  var ovj=["Andre", "Nunung", "Sule", "Aziz", "Parto"];
  
  ovj.insertAll(1, ["Vika", "Armanda"]);
  ovj.remove("Nunung");
  
  data = ovj.map((z)=>"Selamat Datang Kami Ucapkan Kepada " + z.toString()).toList();
  
  data.forEach((x){
    print(x);
  });
  
  }
