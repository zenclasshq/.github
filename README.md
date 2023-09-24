# ZenKlass (ZenClass) Engineering 

Hi everyone, I'm Rodgers (CTO and Co-founder) of ZenKlass.

We're an adaptive learning platform that want give powerful to educators:
- Super easy to use.
- Streamline teaching experience (Educator - Learner Connection is our focus)
- Adapt with any teaching methodology (Teach in your way)

## Our technology:

### Server

We want our server should be fast and safe (`confident`) but it also easy to develop (`development velocity`). So, we choose

- Base: `Rust`, `Postgres`, `Redis`.
- We hide the complexity of rust by using:
  - `async-graphql` -> Declare interface for client in easy way.
  - `diesel-rs` -> work with db and control migration flow with our db.
- Concurrency: `actix` (Actor Model) -> Use resources in an effeciency way.

### Clients

We believe that "client changes faster than server side" like change UI-UX, change system design, etc. So, community is the biggest factor that we choose the technology.

- Website: `ReactJs`, `NextJs`
- Mobile: `React Native`

## Contact?
- Website: https://zenklass.com
- Linkedin: https://www.linkedin.com/company/zenklass/

Want to discuss about technical or any thing that you want to learn about ZenKlass Engineering. Email to: rodgers@zenklass.com

Thanks.
