# character_occurence_in_string

let str = "abcdsabcdacxac";
let obj = {};

for (let i = 0; i < str.length; i++) {
  if (!obj.hasOwnProperty(str[i])) {
    obj[str[i]] = 1;
  } else obj[str[i]]++;
}
console.log(obj);
