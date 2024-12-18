### Hi there 👋

#### Let's keep in touch 👇

[![Udemy][1]][2] [![LinkedIn][3]][4] [![StackOverflow][5]][6]

[1]:  https://img.shields.io/badge/Udemy-A100FF?style=for-the-badge&logo=Udemy&logoColor=white
[2]:  https://www.udemy.com/user/jean-clement/ "My Udemy Profile"
[3]:  https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white
[4]:  https://www.linkedin.com/in/clement-jean "My LinkedIn Profile"
[5]:  https://img.shields.io/badge/Stack_Overflow-FE7A16?style=for-the-badge&logo=stack-overflow&logoColor=white
[6]:  https://stackoverflow.com/users/11269045/cl%c3%a9ment-jean "My StackOverflow Profile"

```proto
message AboutMe {
  option (api_version) = 29;
  option (created_at) = {
    chinese_year: "🐷",
    year: 1995,
    month: NOVEMBER,
    day: 20
  };
  option (kind) = HUMAN;
  option (metadata) = {
    name: "Clément Jean",
    from: "🇫🇷",
    live_in: "🇨🇳",
    languages: [ C, CPP, GO, JAVA, KOTLIN ]
  };
  option (status).work = CODING;
  option (spec).purpose = "Helping others learn Protobuf and gRPC";
  option (favorite) = {
    number: 42,
    programing_language: PROGRAMING_LANGUAGE_UNSPECIFIED,
    emoji_sequence: "🙈🙉🙊"
  };
}
```

Wonder if that ☝️ compiles? Check [here](https://github.com/Clement-Jean/Clement-Jean/blob/main/proto). And credit where credit is due, this idea come from [@BretFisher](https://github.com/BretFisher)'s README.
