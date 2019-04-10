# The Caesar cipher
The Caesar cipher is one of the earliest known and simplest ciphers. It is a type of substitution cipher in which each letter in the plaintext is 'shifted' a certain number of places down the alphabet
![Bored](https://www.thejavaprogrammer.com/wp-content/uploads/2016/11/Caesar-Cipher-in-Java-Encryption-and-Decryption.png)

### Activity

- Create a program to encrypt and decrypt Caesar

- You need to create a class called ``Caesar``
-Inside the class define the Hash ``Plaintext`` and ``Ciphertext`` .

- Create a method ``decrypt`` to decrypt sentences


```ruby 
@Plaintext={
    A:0,B:1,C:2 , D: 3 ,E:4,F:5 ,G:6, H:7,I:8,J:9,K:10,L:11,M:12,N:13,
    O:14, P:15,Q:16,R:17 , S:18 , T:19 ,U:20,V:21 ,W:22,X:23,Y:24,Z:25
}
@Ciphertex  ={
D:0,E:1,F:2 , G:3 ,H:4,I:5 ,J:6,K:7,L:8,M:9,N:10,O:11,P:12,Q:13,
R:14, S:15,T:16,U:17 , V:18 , W:19 ,X:20,Y:21 ,Z:22,A:23,B:24,C:25
}
```
- The mathematical way to decrypt
- Plaintext = Ciphertext - Key mod 26
whereas:

1- Ciphertext: The resulting character is after encryption
2- Plaintext: is the original character before encryption
3- Key: is the encryption key
4- mod: is (modulo operator)
5- 26: is a constant number that does not change because it represents the total number of characters in the English alphabet.
-In this case the key is equal to 3
-  The program takes the sentence and decrypts it
for For example
```ruby
"O ROQK VOFFG"
```
Must be return 
```ruby
"I LIKE PIZZA"
```


  



### Hints:

- Work out how you would do it on paper first! Then start to explain that process in JavaScript.
- Focus on **a single line** before trying to tackle multiple lines!!
  - Hint: A multiple line trip could be considered two single line trips
- Don't worry about prompting the user for input. Hard code some values to get it working. You can use `prompt()` later, if you want, to make it more interactive.
- Consider drawing the lines by sketching out the subway lines and their stops and intersection.
- The key to the lab is finding the index positions of each stop. (hint: `.indexOf()` and `.includes()`)


