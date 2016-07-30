# project64
![Golang peep](https://raw.githubusercontent.com/zyfdegh/project64/master/raw/golang-peep.png)

Golang programming challenge: 64 Go projects in 64 weeks.

# Descriptions
- 2016-07-03 [**call-web-browser**][1]: Open system default web browser and visit a url. Linux/MacOS/Windows supported.
- 2016-07-12 [**mdviewer**][2]: Markdown server, it displays markdown files in your web broswer.
- 2016-07-16 [**njweather**][3]: Call weather.com.cn API and get Nanjing real-time weather, print to screen at last.
- 2016-07-16 [**unqlite-crud**][4]: Golang example to show how to use binder to insert, query, update, delete data(Key and Value) on UnQLite.
- 2016-07-16 [**dockerfile-unqlite**][5]: Dockerfile and essential library and header file for unqlite.
- 2016-07-16 [**random-gen**][6]: An interesting demo showing how to generate random numbers and do a statistic analysis. 
- 2016-07-23 [**local-docker-exec**][7]: Connect to local docker daemon or swarm and run command 'sh' in container.
- 2016-07-23 [**dockerfile-webconsole**][8]: Dockerfile for web console based alpine, it can shell into docker container, powered by gotty.
- 2016-07-30 [**zhy-batch-rename**][9]: Loop to rename directories.
- 2016-07-30 [**remote-docker-exec**][10]: Access docker daemon API, create and run command `sh`. Act like a remote docker exec.


# TODOs

- [ ] Web
	- [X]  [Markdown web previewer][2]
	- [X]  [Call web broswer][1]

- [ ] Alg
	- [ ] Algolrithm Paxos
	- [ ] Algolrithm Raft
	
- [ ] Console
	- [ ] Generate command line program with cobra

- [ ] API
	- [X]  [Get Nanjing weather][3]
	- [ ] etcd v3 API
	- [ ] Docker daemon
		- [X]  [local docker exec][7]
		- [X]  [local docker exec][10]
	
- [ ] Database
	- [X]  [UnQLite CRUD operation][4]
	
- [ ] Dockerfile
	- [X]  [UnQLite][5]
	- [X]  [webconsole][8]

- [ ] Graphical
	- Image processing
	- Chaptcha
	- Chart

- [ ] Goroutine & channel
	- [ ] Multi-thread downloader

- [ ] File system
	- [X]  [Rename directories][9]

- [ ] Others
	- [X]  [Random number generator][3]


[1]:https://github.com/zyfdegh/call-web-broswer
[2]:https://github.com/zyfdegh/mdviewer
[3]:https://github.com/zyfdegh/njweather
[4]:https://github.com/zyfdegh/unqlite-crud
[5]:https://github.com/zyfdegh/dockerfile-unqlite
[6]:https://github.com/zyfdegh/random-gen
[7]:https://github.com/zyfdegh/local-docker-exec
[8]:https://github.com/zyfdegh/dockerfile-webconsole
[9]:https://github.com/zyfdegh/zhy-batch-rename
[10]:https://github.com/zyfdegh/remote-docker-exec
