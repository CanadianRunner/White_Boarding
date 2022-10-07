# White_Boarding
 
Question #1

//Prompt

URLs cannot have spaces. Instead, all spaces in a string are replaced with %20. Write an algorithm that replaces all spaces in a string with %20.
You may not use the replace() method or regular expressions to solve this problem. Solve the problem with and without recursion.

//Questions

Are you okay if I solve this problem with JavaScript?
Can I assume the input will only be strings?
Will I only be replacing the spaces with %20?


//Code


without .replace

example with replace

function replaceSpaces(url)
{
  let replaced = "%20"
  for(let i =0; i < input.lenght; i++)
  {
    if(url[i] == ' ')
      url = url.replace(url[i], replaced);
  }
  console.log(url);
}