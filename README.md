# automysqlbackup
A patched version of automysqlbackup from exoscale.  
Original project can be found at: <http://sourceforge.net/projects/automysqlbackup/>

## howto
git clone  
mkdir /etc/automysqlbackup  
cp ./automysqlbackup.conf /etc/automysqlbackup/  
cp ./automysqlbackup /usr/local/bin/  
chmod +x /usr/local/bin/automysqlbackup  
cp /etc/automysqlbackup/automysqlbackup.conf /etc/automysqlbackup/myserver.conf  

### Edit
vi /etc/automysqlbackup/myserver.conf  

#### [Read More About It](https://github.com/jodumont/automysqlbackup/wiki/README)
