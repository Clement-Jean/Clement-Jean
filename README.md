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
message Clement {
  google.protobuf.Any all_about_me = 1 [
    (api_version) = 26,
    (kind) = KIND_HUMAN,
    (metadata).name = "Clement Jean",
    (spec).purpose = "Help others learn Protobuf and gRPC",
    (spec).locations = {
      type : "Udemy",
      where : "https://www.udemy.com/user/jean-clement/",
    },
    (spec).locations = {
      type : "LinkedIn",
      where : "https://www.linkedin.com/in/clement-jean",
    },
    (spec).locations = {
      type : "StackOverflow",
      where : "https://stackoverflow.com/users/11269045/cl%c3%a9ment-jean",
    },
    (favorite) = {
      number: 42
    }
  ];
}
```

Wonder if that ☝️ compiles? check [here](https://github.com/Clement-Jean/Clement-Jean/blob/main/proto/clement.proto)
