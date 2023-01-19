1. Between Tendermint 0.34 and Tendermint2:
  - // For each single module in github.com/tendermint/tendermint2, in each directory of pkgs/MODULENAME:
  - identify equivalent package in github.com/tendermint/tendermint version 0.34
  - survey all the differences in module, line by line.
  - produce report per module on what bug fixes and changes MUST be be upstream or downstream merged.
     * e.g. the change of the "MEMO" field to "NOTE" is a safety issue, so Tendermint2 should also change MEMO to NOTE.
     * e.g. most changes don't need to be ported for most modules.
     * e.g. TendermintCore can still use EventBus: the change to use the synchronous EventSwitch in Tendermint2 should not be merged.
     * e.g. The indexer for Tendermint2 will be pluggable, so changes to the indexer from TendermintCore is out of scope.
  - create issue on Tendermint 0.34 and/or Tendermint2 with suggested changes.
  - after approval with Tendermint2 team, implement those changes.

2. Between Tendermint 0.34 and the latest version 0.38
  - // the purpose is to keep github.com/tendermint/tendermint 0.34 up to date.
  - // the latest version of Tendermint is 0.38 on github.com/tendermint/tendermint in branch "main_backup".
  - // For every module in github.com/tendermint/tendermint:
  - survey all the differences, line by line. 
  - only suggest bug fixes and maybe few other changes to 0.34.
  - create issue on Tendermint 0.34 with suggested changes.
  - after approval with Tendermint2 team, implement those changes on github.com/tendermint/tendermint.

3. Like 2 but between Tendermint 0.34 and the latest Tendermint fork from Informal.
  - // Like 2, the mission is to keep up to date with bug fixes.

Compare https://github.com/tendermint/tendermint2/blob/master/PRINCIPLES.md to the principles and conventions of TendermintCore
and please respect each project's style and goals.

In 1 and 2, the work is packaged into Github issues/PRs per module.

Some work may fall outside of this template.
