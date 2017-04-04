# Fizz-buzz
Fizz Buzz w/ If/else if/else

for (var i = 1; i <= 100; i++) {
  if (i % 3 === 0 && i % 5 === 0) {
    // Says 'FizzBuzz' after multiples of 5 AND 3
      console.log(' Fizzbuzz');
  } else if (i % 3 === 0) {
    // Says 'Fizz' after multiples of three
    console.log(' Fizz');
  } else if (i % 5 === 0) {
    // Says 'Buzz' after multiples of five
    console.log(' Buzz');
  } else {
    console.log(i);
  }
}
