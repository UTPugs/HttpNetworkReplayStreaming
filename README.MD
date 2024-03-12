# HttpNetworkReplayStreaming Update

Since the dawn of Epic's original replay server, we have migrated to our community-supported servers hosted in the cloud. Loading the replays represent a miniscule portion of the load on the servers, which offers us ability to make certain changes that improve user experience.

## Current list of changes

 - Replays eagerly download in the background regardless of cursor position
 - Increased default cache size to 100mb 

 ## TODO list

  - Persist the cache to allow for loading replays faster between UT instances.

  ## Installation instructions

  Download the [latest release](https://github.com/UTPugs/HttpNetworkReplayStreaming/releases) and copy the DLL to C:\Program Files\UnrealTournament\Engine\Binaries\Win64. 