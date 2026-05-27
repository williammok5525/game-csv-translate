# game-csv-translate
translate language for csv

切记，只做学习之用，不允许商用或任何产生利益的使用

Please remember, this is for educational purposes only and may not be used for commercial purposes or any other profit-making activities.

csv example:

input:

ID,English,Others,Japanese,
aweeklater,A week later...,After this text is disappeared..,一週間後...,
channosig,Poor signal? Something must be wrong with this channel.,"Fucking, hell. No signal....",劣悪な信号？このチャンネルには何か問題があります。,
chanoff,It's off.,It's turned off.,オフです。,

output:

ID,English,Others,Japanese,
aweeklater,A week later...,一周后...,一週間後...,
channosig,Poor signal? Something must be wrong with this channel.,信号不好？这个频道一定有问题。,劣悪な信号？このチャンネルには何か問題があります。,
chanoff,It's off.,关了。,オフです。,
