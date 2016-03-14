# Toggl Button Chrome extension

Add Toggl one-click time tracking to popular web tools.

NOTE: this is fork of [toggl-button](https://github.com/toggl/toggl-button)
as upstream did not consider the changes [mergeable](https://github.com/toggl/toggl-button/pull/207)

## Installing from Source

_Chrome will soon disable all non Chrome Web Store extensions for Windows and
Mac, so this is not viable solution for the future. More info:
https://support.google.com/chrome/answer/2811969_

1.  Clone the repository: `git clone git://github.com/eventum/toggl-button`
2.  Navigate to `chrome://extensions/` and enable "Developer Mode".
3.  Choose "Load unpacked extension..."
4.  Open the src directory in the toggl-button directory you just cloned and follow the prompts to install.

## Change log

List of all the changes and added features can be found at http://toggl.github.io/toggl-button

## Using the Button
1.  Log in to your [Toggl][toggl] account and keep yourself logged in (no need to keep the tab open).
2.  Go to your Eventum account and start your Toggl timer there.

Or start entry from the extension icon menu

3. To edit the running time entry
  - Edit entry details from the post start popup that is shown right after you click the "Start timer" button
  - Edit entry details from the extesnion icon menu by clicking the running duration

4. To stop the current running timer:
  - Press the button again
  - Stop the entry from the extension icon menu
  - Start another time entry inside your account.
  - Go to Toggl to stop or edit your time entry.

## Custom domains
If you use a setup, where one of the supported services is on a custom domain you can customize the extension to fit your needs. Here is a step by step guide on how to [add custom domain][custom-domains] to the extension.

## Contributing

Note, this is fork, you may want to contribute to upstream instead.

[toggl]: https://www.toggl.com/
[custom-domains]: https://github.com/toggl/toggl-button/wiki/Adding-custom-domains
