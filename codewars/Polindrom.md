function isPalindrome(x) {
x=x.toLowerCase();
  let X = x.split("");
  X=X.reverse().join("");
  if(x===X)
    {
      return true;
    }
  else
    return false;
}