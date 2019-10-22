# The Caesar cipher(قيصر) 
The Caesar cipher is one of the earliest known and simplest ciphers. It is a type of substitution cipher in which each letter in the plaintext is 'shifted' a certain number of places down the alphabet
![Bored](https://www.thejavaprogrammer.com/wp-content/uploads/2016/11/Caesar-Cipher-in-Java-Encryption-and-Decryption.png)

### Activity

- Create a program to encrypt and decrypt Caesar

- You need to create a class called ``Caesar``
- Inside the class define the Hash ``Plaintext`` and ``Ciphertext`` .

- Create a method ``decrypt`` to decrypt sentences


```ruby 
Plaintext={
    A:0,B:1,C:2 , D: 3 ,E:4,F:5 ,G:6, H:7,I:8,J:9,K:10,L:11,M:12,N:13,
    O:14, P:15,Q:16,R:17 , S:18 , T:19 ,U:20,V:21 ,W:22,X:23,Y:24,Z:25
}
Ciphertex  ={
D:0,E:1,F:2 , G:3 ,H:4,I:5 ,J:6,K:7,L:8,M:9,N:10,O:11,P:12,Q:13,
R:14, S:15,T:16,U:17 , V:18 , W:19 ,X:20,Y:21 ,Z:22,A:23,B:24,C:25
}
```
- The mathematical way to decrypt :
- `Plaintext = (Ciphertext - Key) mod 26`


- Ciphertext: The resulting character is after encryption
- Plaintext: is the original character before encryption
- Key: is the encryption key
- mod: is (modulo operator)
- 26: is a constant number that does not change because it represents the total number of characters in the English alphabet.
- In this case the `key` is equal to 3
-  The program takes the sentence and decrypts it
for For example
```ruby
"O roqk voffg"
```
Must be return 
```ruby
"I LIKE PIZZA"
```
- The sentences to be decoded : 
```ruby
"oz grcgey ykksy osvuyyohrk atzor oz oy jutk"
```

```ruby
"khkx roqk yvkiogr saynxuusy gtj gznkkx oy g bkmkzgxogt gtj gnskj oy bkxe toik"
```

 #### bonus
  -  Create a method ``encryption`` to encryption sentences ( ``Ciphertext = ( Plaintext + Key) mod 26`` )
  - Print console results in lowercase characters i.e NOT `UPPERCASE` but `uppercase`



### Hints:

- Work out how you would do it on paper first! Then start to explain that process in js.
- **The tools you will need:**  (  ``.split("")`` ,  create a method to get Key By Value !  )
-  create a method to get Key By Value :Returns the key of an occurrence of a given value. If the value is not found, returns nil.  
 

