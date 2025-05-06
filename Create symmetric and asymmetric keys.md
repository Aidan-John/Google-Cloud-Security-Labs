## Activity overview

Encryption is a critical component for protecting data in cloud environments. Security professionals use **cryptography** to transform information into a form that unintended readers can’t understand. Symmetric and asymmetric keys are cryptographic tools used to secure data and enable secure communication over networks. Each type of key has its own distinct differences and can be deployed for different situations.

- **Symmetric Keys:** Symmetric key cryptography uses a single key to encrypt and decrypt data. The same key is used by both the sender and the recipient which is why it's called symmetric. Symmetric key cryptography is efficient and fast.
- **Asymmetric Keys:** Asymmetric key cryptography (also known as public-key cryptography) uses a pair of keys: a public key and a private key. One of the keys is used to encrypt data, while the other key decrypts data. These keys are mathematically related but cannot be derived from each other. Asymmetric cryptography is known for its slow performance. This is due to the use of these two mathematically related keys which are longer than those used in symmetric encryption.

In practice, many secure communication systems use a combination of symmetric and asymmetric cryptography to achieve both efficiency and security. For example, the Hypertext Transfer Protocol Secure (HTTPS) protocol uses asymmetric cryptography for the initial handshake to establish a secure connection, and then switches to symmetric encryption for the actual data transfer.

One of the major problems with symmetric key cryptography involves key distribution. How do you ensure the secure exchange of keys without having the key be compromised or stolen? Asymmetric key cryptography solves this problem by using a public and private key pair. However, it is computationally more expensive, so it’s commonly used for initial key exchange and digital signatures, while symmetric keys are used for the bulk encryption of data.

In this lab, you’ll create both a symmetric key and an asymmetric key to address a request for more space to securely store data.

## Scenario

Cymbal Bank stores and processes large amounts of sensitive customer data including financial transactions and personally identifiable information (PII). The CISO, Javier, wants to protect the confidentiality, integrity, and availability of this data while it's at rest, in transit, and in use. Cymbal Bank wants to transfer a large volume of its data from its on-premises servers to the cloud. Your team lead, Chloe, has suggested using a cloud key management system to create and manage encryption keys to facilitate the secure transmission of this data. You have been tasked with creating a symmetric key and an asymmetric key to support this data transmission.

Here’s how you'll do this task: **First**, you’ll create a symmetric key. **Then**, you’ll create an asymmetric key.
