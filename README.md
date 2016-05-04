#Seneca Attic
To reduce the Seneca project's maintenance overhead, we have evaluated all the available plugins, and have marked a number as possible targets for deprecation.

Our goal is to tidy up the Seneca ecosystem and ensure that our users are provided with well maintained and supported plugins.

We are not killing or un-publishing any plugins, but instead we aim to move them all to this 'senecajs-attic' organisation, where their current status will be more clearly signaled to potential users.

The plugin's readme will be updated to state that it is not being supported by the Seneca organisation, and is not part of our testing process so is not proven to work.

The plugin can still be adopted by new maintainers if it is found to be useful to other developers.

The Seneca organistation (seneca-bot) will be opening issues against these targeted plugins, if the maintainer agrees with deprecating and would like to stop maintaining the target plugin, then they should

1. change the owner of the github repo to the 'seneca-bot' user
2. add the 'seneca-bot' user to npm owners with `npm owner add seneca-bot`

seneca-bot will then update the readme for the plugin and move it to the senecajs-attic organisation.

If the maintainer feels that the plugin is still needed by themselves or their organisation, they can close the issue and we will view the plugin as a third party plugin outside of the Seneca organistion.
