# Instructions  

Are you a cat person or a dog person? The code below prints a nice message about cats, but if you’re a dog person, you might not agree.

## Steps
1. Write some code below that changes every occurrence of “cat” to “dog” in the message. This code will be more like the first program in this lesson where we replaced 1’s with l’s.

2. (Optional - not autograded) add a counter to count the number of replacements and print it out.

3. (Optional - challenging and not autograded) What if you like both cats and dogs? After you replace “cat” with “dog”, add another loop that looks for the word “dogs” and adds ” and cats” to it. Do not replace “dog”, just replace “dogs”. This will just replace the first sentence in the example below but you can add other sentences to test. For this loop, you will need to use a special version of indexOf that searches from a given index, so that you don’t end up with an infinite loop that keeps finding the first “dogs”. Make sure you add a variable fromIndex that is initialized to 0 and that is changed each time through the loop to skip over the last word that was found.
    - int indexOf(String target, int fromIndex) searches left-to-right for the target substring, but starts the search at the given fromIndex. You are not required to know this version of indexOf for the AP CS A exam, but you can use it (and any valid Java code) in the Free Response Questions.  