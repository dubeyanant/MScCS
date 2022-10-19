# Introduction to The Concepts of Network Security

## Modern Nature of Attacks

1. **Automating Attacks**: Humans dislike mundane and repetitive tasks. Automating them can cause financial destruction or a security nuisance quite rapidly.
2. **Privacy Concerns**: Companies collect, collate, polish and format all sorts of data and are willing to give this information to whoever pays highest. This can lead serious privacy concerns for common people.
3. **Distance Does Not Matter**: Attacker can perform security attacks from their home, in this modern era distance does not matter.

## Security Approaches

- A **trusted system** is a computer system that can be trusted to a specified extent to enforce a specified security policy. A trusted system should be:
    - Tamper proof.
    - Always be invoked.
    - Small enough so that it can be tested independently.
- **Bell-LaPadula Model** is a model in which a highly trustworthy computer system is designed as a collection of objects and subjects. Objects are passive repositories or destinations for data, such as files, disks, printers, etc. Subjects are active entities, such as users, processes, or threads operating on behalf of those users.

### Security Models

1. **No Security**: The approach could be a decision to implement no security at all.
2. **Security through Obscurity**: A system is secure simply because nobody knows about its existence and contents. This approach doesn’t work for too long.
3. **Host Security**: The security for each host is enforced individually. This is a very safe approach, but it cannot scale well.
4. **Network Security**: The focus is to control network access to various hosts and their services, rather than individual host security. This is a very efficient and scalable model.

## Principles of Security

### Confidentiality

- It specifies that only the sender and the intended recipient should be able to access the contents of a message.
- Confidentiality gets compromised if an unauthorized person is able to access a message.
- If the message is accessed by C without the permission or knowledge of A and B. This type of attack is called **interception**.

![Untitled](Diagrams/Untitled.png)

### Authentication

- Authentication mechanisms help establish proof of identities. The authentication process ensures that the origin of an electronic message or document is correctly identified.
- If C pretends to be A and sends some message to B than this type of attack is known as **fabrication**.

![Untitled](Diagrams/Untitled%201.png)

### Integrity

- If the contents of the message is as it is when it reaches the receivers than we say that the integrity of the message is not lost.
- If the message is change by C before it reaches to B than this type of attack is called as **modification**.

![Untitled](Diagrams/Untitled%202.png)

### Non-repudiation

- A sends some message to B and later on denies it, this is called as repudiation. Non-repudiation defeats such purpose.

![Untitled](Diagrams/Untitled%203.png)

### Access Control

-