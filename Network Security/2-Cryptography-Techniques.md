# Cryptography Techniques

## Table of Contents

- [Table of Contents](#table-of-contents)
- [Introduction](#introduction)
- [Plain Text and Cipher Text](#plain-text-and-cipher-text)
- [Substitution Techniques](#substitution-techniques)
- [Transposition Techniques](#transposition-techniques)

## Introduction

**Cryptography** is the method to achieve security through encoding the message to make it non-readable.

<img src="Diagrams\2_1.png" style="zoom:60%;" />

**Cryptanalysis** is the technique to decoding the message from non-readable form to readable form without knowing how they were encrypted before.

<img src="Diagrams\2_2.png" style="zoom:60%;" />

**Cryptology** is a combination of cryptography and cryptanalysis.

## Plain Text and Cipher Text

Any human readable language is known as **plain text** or **clear text** i.e. A plain text signifies a message that can be understood by the sender, the receiver and also by anyone who has access to that message.

When a plain text is encrypted using any encryption algorithm, the resulting message is called **cipher text**.

<img src="Diagrams\2_3.png" style="zoom:60%;" />

**Substitution** and **transposition** are the two primary ways in which a plain text can be encrypted. When these two techniques are used together we call it as **product cipher**.

## Substitution Techniques

The technique of replacing an alphabet one three places down was first proposed by Julius Caesar and is known as **Caesar cipher**. In the substitution-cipher technique, the characters of a plain text message are replaced by other characters, numbers or symbol.

In the **modified Caesar cipher** the alphabets need not shift only three places down but rather can shift to any place in the total of 25 remaining alphabets uniformly. A cryptanalyst can easily brute force their way through in this technique.

**Mono-alphabetic cipher** replaces the alphabets randomly.

In the **Homophonic substitution cipher** one plain-text alphabet can map to more than one cipher-text. For instance, A can be replaced by D, H, P, R.

In the **Polygram substitution cipher** a block of alphabets is replaced with another block.

## Transposition Techniques

