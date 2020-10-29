# Writeup for diffeRent_but_SimilAr

###### This challenge is about implementing RSA (As the UpperCase alphabets in challenge name suggest) whose public key is a product of two irreducible polynomials

- **Resource to quickly learn and implement: http://www.diva-portal.se/smash/get/diva2:823505/FULLTEXT01.pdf**<BR>(One of top results that one might see when they google `polynomial rsa`)

- **Understanding the encryption script**
    - Make A polynomial
    ```python
    P=PolynomialRing(GF(2),'x')
    n_poly = P(n)
    R.<a> = GF(2^2049)
    ```

- Seeing
