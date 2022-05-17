# The `a314.xyz` project

[a314.xyz](https://a314.xyz) is a collection of potentially useful, purpose-specific HTTP APIs exposed at the eponymous domain.

Instead of (RESTfully) exposing resources, these APIs provide functionalities that could be categorized as forward proxies, webhooks, or API Augmentation &#8482;<sup>?</sup>, among others.

It is a pet project, born out of boredom, and admiration for APIs and the Web.


# API listing

Below is a list of the available APIs, each at the subdomain in parentheses. The categories under which each API falls are included in brackets (see legend at the bottom).

For example: APProxy is available at **pro**.a314.xyz and is categorized as "API augmentation" and "forward proxy".

**Furthermore, each API exposes its docs at path `/docs`**.
<br/><br/>

### **APProxy** (`pro.`) [AA, FP]

APProxy is a forward proxy HTTP API used to intercept
and modify responses from origin servers.<br/>
By exposing convenient and common operations it can do
away with inconvenient or boilerplate implementations.

<!-- TODO: add?

### **RecNet** (`rn.`) [ML]

TODO:

### **TempExpo** (`tx.`) [AA, FP]

TODO:

-->

### **Tipot** (`tip.`) [AF, ML]

Tipot is an AI/ML/DL NLP HTTP REST API optimized for acronym length.<br/>
For now the one supported use case is completion of incomplete sentences but

### **WebValve** (`wv.`) [AA, WH]

WebValve is an HTTP API microservice that calls registered
webhook endpoints once given conditions are met.<br/>

## Categories
    AA : API augmentation
    AF : API fun
    FP : forward proxy
    ML : AI/ML/DL
    WH : webhooks (or similar)


# NOTE:s on no-nos & oh-nos

### Reliability
- Do not count on the ...
	1. availability
	2. consistency
	3. performance
- ... of any of these APIs in your production apps, as I may ...
	1. close or take down
	2. change (without versioning)
	3. constrain the computational resources of
- ... any of them on no notice at all.
- IANAL, but you may consider these remarks as the (legally unbinding) SL(D)A that you enter into by using any of these APIs, none of which are battle-tested (nor skirmish, or even scuffle, for that matter)
- I dare do this, because I work on this project for fun and free on my free-time and time-off from work!

### Alternatives
- In case you find a corresponding API that better suits your needs, then by all means use that one. I may not even look into the potential existence of similar solutions, whenever I come up with an idea that I want to implement for enjoyment.

### Tech(nicalities)
- Here I may (many may say) use the term "Web API" somewhat loosely, instead of sticking strictly to the perhaps more precise term "HTTP API" (or even "REST"), while reserving Web API for client-side (JavaScript) APIs exposed within browsers. Furthermore, some of these APIs may extend (or stretch) the definition even further, by e.g. exposing "app-like" functionality. Do REST easy, please-y!

### End-of-Rant
- EOR! With these words of warning out of the way, I warmly welcome ...
1. Feedback & feature requests (but do not hold your breath)
2. Business inquiries (in which case you can, of course, expect a more professional approach from yours truly)
- ... You will find my contact info on my personal GitHub profile README. **Thanks**!


# FQA

**A**: No, this is intentional, as in fact, I came up with these questions myself. The rest are presented in the typical order to curb bafflement and silliness.\
**Q**: Shouldn't Q come before A? How do I even know to ask this?
<br/><br/>

**Q**: Is that a typo? Don't you mean FAQ?\
**A**: No. See next question.
<br/><br/>


**Q**: What does FQA stand for?\
**A**: Frequently Questioned Answers. Duh!
<br/><br/>

**Q**: What languages, libraries, technologies, frameworks, etc. do you use?\
**A**: Non-exhaustive list (**a BIG thanks** to the authors, maintainers & communities, and sorry for any notable omissions):
- Python
	- Flask
  - Flasgger
  - NumPy & pandas
  - TensorFlow & Keras (+ scikit-learn)
- Node.js (with TypeScript)
	- Express.js
  - Swagger UI Express & swagger-jsdoc
  - Node Fetch
  - Mongoose
- MongoDB (Atlas)
- AWS (EB, EC2, ETC)
- Docker
- Linux
- (Dev)
  - ESLint
  - Nodemon
<br/><br/>

**Q**: What about GraphQL, huh?\
**A**: As it says in the acronym, Graph**Q**L is a query language for APIs that expose resources. These APIs expose functionalities, for example acting as forward proxies (see project description at the top). 

<!-- TODO: Money lyrics link -->
**Q**: What about [insert hip lib]?\
**A**: *I'm alright, Jack, keep your hands off of my stack*! But thanks, I will be glad to check that out!

**Q**: Will you open source the code for (any of) the APIs?\
**A**: I might at some point. Not for now, though, to/for:
- Sacrifice readability for alleged elegance (the compiler/interpreter does not care, but I do beg your partial pardon [PEP 20](https://peps.python.org/pep-0020/))
- Hold on to my numerous & superfluous, barely-sensical `# NOTE:s` &nbsp;&&nbsp; `// NOTE:s`
- Preserve personal peace of mind
- Prevent public piece of mind
- Make my commits care-free
- Conceal my silly mistakes
- Hide the bad (ha)bits
- For my Zen's sake


# TODO:s

- Todos los to-dos
- *Instead of relying on a roadmap, I navigate by the stars, which, unfortunately, rarely align.*<br>Do consider leaving one, especially if you like what I'm doing here!
