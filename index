function palindrome(str) {
  let remove = /[\W_]/g;
  let lowCaseStr;
  let reverseStr;

  lowCaseStr = str.toLowerCase();
  lowCaseStr = lowCaseStr.replace(remove, '');
  
  reverseStr = lowCaseStr.split(''); 
  reverseStr = reverseStr.reverse();
  reverseStr = reverseStr.join('');

  return reverseStr === lowCaseStr;
}
