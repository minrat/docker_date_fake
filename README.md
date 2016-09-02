# docker_date_fake
This is a way to cheat the system ,get the current system time(set by yourself)

more information , please refer to https://github.com/wolfcw/libfaketime

export LD_PRELOAD=/usr/local/lib/faketime/libfaketime.so.1
export FAKETIME="-30d"
