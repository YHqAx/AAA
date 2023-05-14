# This was an attempt at microservices that is not complete.
# This microservice is supposed to receive data from a sensor in a JSON file.
# Storage would be MongoDB and FSgrid.
#  I wanted to make the sensor data into a visualisation but did not get that point.
# Why is it not complete?
# Because the PC I did it on originally crashed and the harddrive got corrupted with no backups. (not a big deal)
# Second try is this try and I checked these concepts quite deeply.
# I got to the point where I wanted to use postgres for the SQL REST API but found out that my linux distribution does not allow mysql- server to be downloaded nor mariadb.
# I also cannot download another distribution and copy the storage because I do not have enough memory. 
# Anyways I gave up with kubernets on linux and k9s, and instead tried Kubernetes on AWS...  Understood a bit more but complete dead end.
# The YAML files used for the configuration of the Kubernetes nodes I understood the basics of constructing them, but no idea about the different kinds that can be used and what to insert in them other than the deployment, gateway service and ingress types.
# Also I used rabbtimq-servermanager, but in my ingress.yaml file I have the alias as rabbitmq-manager.com but it doesn't work? So I connected to it via the IP address which I got from k9s rabbitmq nodes shell. But sometimes it did not connect even with the IP, and never localhost. So rabbitmq sucks. 
#
#
# I do not expect anything from this really.
