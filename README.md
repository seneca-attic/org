#Seneca Attic
To reduce the seneca project's maintenance overhead, we have evaluated all the available plugins,and have marked a number as possible targets for deprecation.

Our goal is to tidy up the seneca ecosystem and ensure that our users are provided with well maintained and supported plugins.

We are not killing or un-publishing any plugins, but instead we aim to move them all to this 'seneca-attic' organization, where their current status will be more clearly signaled to potential users.

The plugin's readme will be updated to state that it is not being supported by the seneca organization, and is not part of our testing process so is not proven to work.

The plugin can still be adopted by new maintainers if it is found to be useful to other developers.

If you as the maintainer of one of these target plugins agree with this, and would like to stop maintaining the target package, please

1. accept the deprecation pull request made by the 'seneca-bot' user
2. change the owner of the github repo to the 'seneca-attic' organization
3. add the 'seneca' user to npm owners with `npm owner add seneca`

If you feel that the plugin is still needed by yourself or your organization,
no action is needed on your part and you can close the pull request.

We thank you for your time,

sincerely, the seneca project.
