# GetSum

const getSum = (numb) => 
String(numb).split('').reduce((acc, item) => 
acc + Number(item) , 0);
