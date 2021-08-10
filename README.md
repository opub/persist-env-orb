# persist-env-orb

CircleCI Orb to handle persisting environment variables across executors with different operating systems. e.g. an environment variable of `FOO=BAR` can be persisted in a Linux Docker executor and then attached and used from a Windows executor.

It can be found in the CircleCI Orb Registry at https://circleci.com/developer/orbs/orb/opub/persist-env-orb.

This orb is based on the https://github.com/christeredvartsen/circleci-persist-env-vars-orb implementation.

If new to CircleCI orb creation the [Manual Orb Authoring Process](https://circleci.com/docs/2.0/orb-author-validate-publish/) is much easier to follow for simple orbs like this. See the [Publishing Orbs](https://circleci.com/docs/2.0/creating-orbs/) page for versioning details. The full-blown [Orb Authoring Process](https://circleci.com/docs/2.0/orb-author/) is the CircleCI recommended method but I found it too complex for any simple orb work I was doing.
