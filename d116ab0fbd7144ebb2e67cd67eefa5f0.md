# 修改他人的 PR

**比如我要修改 name=libangzhu branch chain33-p2p-listenPort 的 pr**

- ##### 拉取要修改的分支

  ```bash
  make pull name=libangzhu b=chain33-p2p-listenPort
  ```

  make pull 的源码：

  ```makefile
  pull:
  	@remotelist=$$(git remote | grep ${name});if [ -z $$remotelist ]; then \
  		echo ${remotelist}; \
  		git remote add ${name} https://github.com/${name}/chain33.git ; \
  	fi;
  	git fetch ${name}
  	git checkout ${name}/${b}
  	git checkout -b ${name}-${b}
  ```

  然后修改代码，修改完成后,并且在本地 commit

- **push已经修改好的内容**

  ```bash
  make pullpush name=libangzhu b=chain33-p2p-listenPort
  ```

  make pullpush 的源码：

  ```makefile
  pullpush:
  	@if [ -n "$$m" ]; then \
  	git commit -a -m "${m}" ; \
  	fi;
  	make pullsync
  	git push ${name} ${name}-${b}:${b}
  ```

  



id: d116ab0fbd7144ebb2e67cd67eefa5f0
parent_id: dea12b90879a4f71bb5eab53adc7286a
created_time: 2021-03-28T01:16:47.681Z
updated_time: 2021-03-28T01:20:11.348Z
is_conflict: 0
latitude: 0.00000000
longitude: 0.00000000
altitude: 0.0000
author: 
source_url: 
is_todo: 0
todo_due: 0
todo_completed: 0
source: joplin-desktop
source_application: net.cozic.joplin-desktop
application_data: 
order: 0
user_created_time: 2021-03-28T01:16:47.681Z
user_updated_time: 2021-03-28T01:20:11.348Z
encryption_cipher_text: 
encryption_applied: 0
markup_language: 1
is_shared: 0
type_: 1