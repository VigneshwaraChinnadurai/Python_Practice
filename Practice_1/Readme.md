Though we are not using numpy, for best practice imported numpy.

Our question here is to get combinations as mentioned in the image (Question1_part*) and count the combinations which starts with vowels and consonants.

For storing the possible combinations, creating an empty list as combinations=[].

Reason for B declaration= Here it is programmed to start iterate from string[0] initially. So in second iteration, it should start from string[1] and so on for further iterations.

Value os String is got in runtime.

let me explain the program in short,
1st we need to split the values to get possible combinations,
2nd we need to split for increasing value till it reaches the length of the string,
3rd we need to do the above steps initially starting index 0 to its max value of the string.
4th and main point is we don't want repetitive values. In order to avoid it, introducing the new variable 'b' with increasing value.
Last buut not the least, we should store the new possible value from our code as possibilities.

Finally we will get the possible expected combinations which is stored in possibilities.

For Kevin's output, taking the count of the all possible outcomes which starts with vowel. ('Vowel')

And for Stuart's result, taking the count of the all possible outcomes which starts with consonants. (combinations-vowel)



As this is my first writing in git, please forgive me if you find any mistakes.


Kind Regards,,
Vignesh.
