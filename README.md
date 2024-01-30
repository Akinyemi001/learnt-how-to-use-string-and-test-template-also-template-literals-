# learnt-how-to-use-string-and-test-template-also-template-literals-

// string and test template

const firstname = 'john';
const job = 'teacher';
const birthdateyear = 1991;
const year = 2023;
// string
const john = "i'm a," + firstname + ' a '+(year - birthdateyear)+'year old '+ job+'!';
console.log(john)
// template literals
const dohn = `i'm ${firstname} a ${year-birthdateyear} years old ${job}`;
console.log(dohn)

// WRITING A CODE TO DETERMINE IF YOU CAN DRIVE

const age = 15;
if(age >= 18){
    console.log('you are good to good');
}else{
    const yearleft = 18 - age;
    console.log(`you are too young too drive, wait for another ${yearleft} years more`);
}
