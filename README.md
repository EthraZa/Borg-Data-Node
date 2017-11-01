# Borg Data Node

> Data nodes were portable storage and processing devices utilized by the Borg to archive and transfer information. Multiple ones would be used on a ship to > store data on its Borg drone manifest and tactical information, such as long-range sensor telemetry, assimilation logistics, and other starship movements.
> - [Memory Alpha](http://memory-alpha.wikia.com/wiki/Data_node)

In other words a Data node is an external Hard Drive or Storage that backups important data.
To get the data backed up, The Borg Collective uses a very advanced piece of software, full of [Borg algorithms](https://github.com/borgbackup/borg/tree/master/src/borg/algorithms), named [Borg Backup](borgbackup.readthedocs.io).

This program is a cross-platform Graphical User Interface for [Borg Backup](borgbackup.readthedocs.io) so you, dear future Borg drone, can easily get your data into your Data Node.

---

### Specifications this project adheres to

- [Semantic Versioning](http://semver.org/spec/v2.0.0.html)
- [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
- [JavaScript Standard Style](https://standardjs.com/)
	- But with **Tabs** for indentation and **Semicolons**

### Main projects in use

- [NW.js](https://nwjs.io/)
- [Vue.js](https://vuejs.org/)
- [Vue Material](http://vuematerial.io)

---

### Wireframe mockup

![Mockup](https://github.com/EthraZa/Borg-Data-Node/blob/master/promo/img/Borg_Data_Node-Mockup.svg)
Made with [Draw.io](https://www.draw.io/)

---

### Considerations

I have discovered Borg Backup just about one week ago (2017-10), when researching backup alternatives to replace my current Rsync script to backup my servers.
I have already converted my script to work with Borg and I'm gradually starting to backup stuff with it, still in parallel with Rsync. If you want to take a look at it, it's here [BorgBackup.sh](https://gist.github.com/EthraZa/6cd402c3f461b01b23ab3f4166ae829e). It was made to centralize the management and the backups in the storage server. So it is in the cron of the storage server, remotely starting other servers backup in sequency.

Besides to learning more about Borg Backup, this project is also my very first project with Vue.js, something I'm expecting to learn for some time already, to replace my use of ExtJs in the future. So if you find some dumb mistake here, please be welcome to point it out and I'll gladly take a look at to improve it.

I expect to have something to show of in one or two months from now, It will depends more on the Vue.js learning curve. 
I'll at least commit the Changelog, with the task list, to let anyone interested to know how the project is doing.

Also, any comments are very appreciated, so go ahead, create issues and lets talk about it.

---

### License

Not sure yet! MIT, BSD, Apache, whatever, pick one.
