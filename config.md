<!-- database -->
NAME: taiga
USER: taiga
PASSWORD: p0St9R35t4iG9
HOST: 127.0.0.1
PORT: 5432

<!-- rabbitmq -->
NAME: taiga
USER: taiga
PASSWORD: r48bi7mQt4iG9
HOST: 127.0.0.1
PORT: 5672
amqp://taiga:r48bi7mQt4iG9@127.0.0.1:5672/taiga

sudo rabbitmqctl add_user taiga r48bi7mQt4iG9
sudo rabbitmqctl add_vhost taiga
sudo rabbitmqctl set_permissions -p taiga taiga ".*" ".*" ".*"

<!-- secret -->
SECRET: 5Ecr37t4iG9

http://taiga-diskominfo.bandung.go.id/