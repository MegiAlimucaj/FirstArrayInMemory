# FirstArrayInMemory
First Array In Memory
//Instructions 
//Given an array of strings, words, return a string that has all the words concatenated together
// - spaces are needed in between words
//
//ex. ['how', 'are', 'you'] -> 'how are you'

function wordsToSentence(words) {
  //your code here
  var Sentence = '';
  for (let i = 0; i < words.length; i++){
    Sentence = Sentence + words[i] + ' ';
  }
  return Sentence.trim();
}

//console log results
console.log('results', wordsToSentence(['hey', 'there']));

//don't change this line
module.exports = {wordsToSentence};
