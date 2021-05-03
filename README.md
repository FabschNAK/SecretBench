# SecretBench
### Intro

---

SecretBench is a benchmark for secret scanning tools to evaluate false negative rates.
It is composed of several batteries of various credentials, keys, and tokens, with a wide variety of formatting and syntax  variations. The end-goal of this project is to ensure that all secret scanning software can adequately handle such variations, thus reducing then number of false negatives for all users.

### Why?

---

False positives and false negatives are two distinct issues. While false positives are annoying, produce alert fatigue, and contribute to malaise within the information security space, false negatives can directly lead to actual security incidents. There are many resources on reducing false positives across the web, but I struggled to find many resources at all on reducing false negatives. I posit that vendors will struggle to systematically and efficiently reduce false negatives on the basis that they're inherently not aware of those cases, and would be relying entirely on in-house R&D or user reports to identify new false negatives. This projects aims to be a nexus for false negative data, and to share that data with those vendors so that all vendors can benefit from knowledge of these false negative cases. Hopefully, this ultimately will help to keep more companies and more people safe from security incidents.

### Disclaimer

---

The original battery borrows entirely from a project I previously collaborated on, OWASP SEDATED [OWASP](https://owasp.org/www-project-sedated/), [Github](https://github.com/OWASP/SEDATED).
As such, includes a copy of OWASP SEDATED's license, and this shout out to my homies Dennis and Simeon :)

### What I will do

---

- I will be adding to the battery over time as experience and research allows me to find methods of secret usage not covered by the existing battery.
- I eventually will begin publishing functional comparisons between secret scanning solutions based on this, to better aid security professionals in choosing which secret scanning solution to use.
- I will actively collaborate with the developers/maintainers/owners of secret scanning solutions to help them add their false negative cases to their scanners.
- I will happily accept contributions from the open source community, vendors, third party companies, and individuals.  
- I may update this README as I see fit as the project grows

### What I won't do

---

- I will not monetize this project.
- I will not accept money to publish false results in the aforementioned functional comparisons.
- I will not compromise the integrity of the batteries by removing any tests on the basis of false positives.
- I will not help vendors write code to actually detect these false negatives within their commercial product.

### Contact

---

Feel free to email me at <ryan.delaney@owasp.org>, or to connect with me on <https://www.linkedin.com/in/infosecrd/>.