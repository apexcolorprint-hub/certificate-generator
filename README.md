# E-Waste Certificate Generator

Customer ka data paste karke E-Waste Recycling Certificate (PDF / PNG) banane ka tool.
Ye ek single `index.html` file hai: koi server, install ya internet library ki zarurat nahi.

## Features
- Customer data paste karo -> Certificate No., Date, Kgs, Company, Address, Pickup Date apne aap nikalta hai
- Pickup Date me do dates (From - To) ho to auto "Pickup Date from : ... to ..." ban jata hai
- Address optional hai
- Multiple certificates list me save karo, phir sab ek PDF ya ZIP me download karo
- Template Edit: naya certificate design upload karke text ki jagah set karo
- HD PDF / PNG download

## Online chalane ke liye (GitHub Pages)
1. GitHub par naya repository banao (jaise `certificate-generator`).
2. `index.html`, `README.md` aur `.nojekyll` upload karo.
3. Repository `Settings` -> `Pages` -> `Build and deployment`:
   - Source: `Deploy from a branch`
   - Branch: `main` aur folder `/ (root)` -> `Save`
4. 1-2 minute baad link milega: `https://<aapka-username>.github.io/certificate-generator/`

## Computer par chalane ke liye
`index.html` ko Chrome ya Edge me double-click karke kholo.

## Dhyan rakhein
- Saved list aur templates browser me store hote hain. Browser ya computer badalne par wo nahi dikhenge.
- Public repository ka link kisi ke bhi paas ho to wo tool khol sakta hai, aur certificate ki base image bhi dekh sakta hai.
