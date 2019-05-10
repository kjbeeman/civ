# Cloud Init Verifier

## Why this container image?

Easy, I couldn't find one that already existed, and didn't feel like installing cloud-init on my development system.

## Why Ubuntu, and not something smaller?

Got this working in about five minutes, and for my use case, I'm not concerned with the overall size of the image. 

## How do I use this?

`docker run -v $DIR_WITH_CLOUD_INIT:/ cloud-init-verifier $cloud_init_file`

## It doesn't work!

This is just a container to setup to run the cloud-init verifier script. If it doesn't work, there isn't much I can do about it. 

## Why doesn't the cloud-init team offer a container?

Maybe they do? I didn't find it so I created this one. Maybe they are busy with actual features and assume anyone who wants to container image can just create one. 

