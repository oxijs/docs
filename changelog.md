# Changelog for v2.2.0

> Changes that were planned for v2.1.0 have been delayed for the moment.

### Features and improvements

> **New functions**: [`$advancedReplaceText`](https://oxi.js.org/functions/custom/advancedreplacetext), [`$getCommandNames`](https://oxi.js.org/functions/custom/getcommandnames), [`$commandExists`](https://oxi.js.org/functions/custom/commandexists)&#x20;
>
> Rewrote code for all custom functions.&#x20;
>
> `$imageWidth` and `$imageHeight` have been deprecated.&#x20;
>
> Improved log messages.&#x20;
>
> The code for `$formatDate` was rewritten so that it no longer uses an external API, but rather a modification of the old code.&#x20;
>
> New option for `$getGuildAutomodNames`: _separator_
>
> ```php
> $getGuildAutomodNames[guildID?;separator?]
> ```
