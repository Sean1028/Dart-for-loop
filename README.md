# Dart-for-loop
void main(){
  
  List <String> menlist=["王曉明" , "李小菜" , "雲育鏈"];
  
  print (menlist[0]);
  
  for(int index=0; index<menlist.length;index++){
    print(menlist[index]);
  } 
  
  for(String men in menlist){
    print(men+ "送早餐給小美");
    
  } 
}
