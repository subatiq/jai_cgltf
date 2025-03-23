# cgltf bindings for Jai

This repo contains header file for cgltf and some copy pasted code (I think from STBI module from jai) to autogenerate bindings. It lets you update bindings to the newest version on your own. Just put updated header file into `source` directory and run

```
jai generate.jai
```

It will generate `bindings.jai` and you can start using the library.

