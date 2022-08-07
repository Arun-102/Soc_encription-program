The RSA algorithm code procedure:<br /><br />
1. The initial procedure begins with selection of two prime numbers namely p and q, and then calculating their product N.<br />
2. Consider number e as a derived number which should be greater than 1 and less than (p-1) and (q-1). The primary condition will be that there should be no common factor of (p-1) and (q-1) except 1.<br />
3. The specified pair of numbers n and e forms the RSA public key and it is made public. Generates key of size 1024 bits.<br />
4. Private Key d is calculated from the numbers p, q and e. The mathematical relationship between the numbers is as follows:  ed = 1 mod (p-1) (q-1).<br />
5. Encryption Formula: C = Pe mod n.<br />
6. Deceyption Formula: Plaintext = Cd mod n.<br />
