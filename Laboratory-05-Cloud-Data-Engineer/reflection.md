# Mission Reflection

This laboratory activity helped me understand why object storage is useful
in cloud computing. Object storage is better suited for storing millions of
photos because it is designed for large amounts of unstructured data. Each
photo can be stored as an object with its own metadata, making it easier to
manage a large collection of images.

Docker made deploying MinIO easier because I did not need to manually install
and configure every component. I only needed to run one Docker command to
download and start the MinIO server. Docker also allowed me to configure the
required ports and environment variables during deployment.

A bucket is a container used to store and organize objects in object storage.
In this activity, I created a bucket named `client-photos`. The bucket was
used to store the sample file that I uploaded through the MinIO web console.
A real photo-sharing application could use a bucket to store many user
images.

Large enterprise companies can protect their object storage data from
physical server failures by keeping multiple copies of the data. They can
also use replication, backups, redundant servers, and different storage
locations. These methods help reduce the possibility of losing important
data when hardware fails.

My confidence in using the Linux command line is growing as I complete more
cloud computing activities. I am becoming more comfortable running commands,
checking Docker containers, and troubleshooting problems. This activity also
helped me understand how command-line tools and cloud services work together.
I learned that cloud engineers need both technical knowledge and practical
skills when managing cloud infrastructure.
