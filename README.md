# sentinella

I wrote Sentinella 'cause I have lot of virtual machines at home, plus some _raspberry pi_. 
Then I needed a _quick'n dirt_ way to have a look to their status.

It listens on http://<machine>:8080 , giving you informations about the machine itself.(ps. netstat, and more)

It is supposed to work in local, _NAT-ted_ networks.

This is why it has no ssl, and this is the reason you should <h2>NOT expose it to the internet</h2>.

Sentinella is written in go, just type "go build ." into its folder to have it.
To deploy it, just copy the executable and start it.


Is tested on:

    +freebsd-arm machines
    +freebsd-386 machines
    +raspbian-arm machines
    +debian-386 machines
    +debian-x64 machines

have fun.

P.S: no, it won't work on Windows.
