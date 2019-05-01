# Language Generation
```
$ git clone https://github.com/hskaailabnlp/language_generation.git
$ cd language_generation
$ docker build -t ai_lab:2 .
$ cd ..
$ docker run --runtime=nvidia -p 8888:8888 -v $(pwd)/language_generation:/tf/notebooks ai_lab:2
```