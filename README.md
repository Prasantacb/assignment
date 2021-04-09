# assignment
//  https://github.com/Prasantacb/assignment

// 01 kilometerToMeter
function kilometerToMeter(kilometer){
    var meter = 1000;
    for (let i = 0; i <= kilometer; i++) {
        var total = meter * kilometer;
    }
    return total;
}
var totalMeter = kilometerToMeter(10);

// 02 budgetCalculator
function budgetCalculator(watch, phone, laptop){
    let watchPrice = 50;
    let phonePrice = 100;
    let laptopPrice = 500;
    
    var totalWatch = watchPrice * watch;
    var totalPhone = phonePrice * phone;
    var totalLaptop = laptopPrice * laptop;
    
    var totalPrice = totalWatch + totalPhone + totalLaptop;
    return totalPrice;
}
var sum = budgetCalculator(4, 5, 2);

// 03 hotelCost
function hotelCost(hotelNight){
    let cost = 0;
    if(hotelNight <= 10 ){
      cost = hotelNight * 100;
    }
    else if (hotelNight <= 20){
      let fistPart = 10 * 100;
      let remaining = hotelNight - 10;
      let sceondPart = remaining * 80;
      cost = fistPart + sceondPart;
    }
    else {
      let fistPart = 10 * 100;
      let sceondPart = 10 * 80;
      let remaining = hotelNight - 20;
      let thirdPart = remaining * 50;
      cost = fistPart + sceondPart + thirdPart
    }
    return cost;
}
let totalCost = hotelCost(25);

// 04 ferndsName..
    var ferndsName = ['jibo', 'PrasantaCb', 'rakib', 'raju', 'JibonRoy'];
    var max = ferndsName[0];
        for(var i = 0; i < ferndsName.length; i++){
            var element =  ferndsName[i];
            if (element > max){
                max = element;
            }
        }
