/* HORIZONTAL SERVER LIST BY PURPLE WIZARD */

.base-3dtUhz {
	z-index: 1;
	position: absolute;
	top: calc(15px + 10px * var(--ServerColumns) + var(--ServerSize) * var(--ServerColumns));
	left: 0;
}

.platform-osx .base-3dtUhz {
	top: calc(57px + var(--ServerSize) * var(--ServerColumns));
}

.root-SR8cQa {
	width: calc(100vw - 265px);
	top: calc(48px + var(--ServerSize) * var(--ServerColumns))
}

#app-mount:before {
	content: "";
	position: absolute;
	top: 22px;
	left: 0;
	right: 0;
	background: var(--TitleBG);
	height: calc(15px + 10px * var(--ServerColumns) + var(--ServerSize) * var(--ServerColumns)) !important;
}

.platform-web #app-mount:before {
	top: 0;
}

.guilds-1SWlCJ {
	background: transparent !important;
	padding-top: .25em;
	width: 100%;
	position: unset;
	height: 100%;
	width: 100%;
}

.guilds-1SWlCJ .scroller-2TZvBN {
	display: flex;
}

#app-mount .wrapper-21YSNc [role=group] a.wrapper-1BJsBx>.icon-27yU2q {
	width: calc(var(--ServerSize) - 10px);
	height: calc(var(--ServerSize) - 10px);
}

.expandedFolderBackground-2sPsd- {
	border-radius: .25em 0 0 .25em !important;
}

.expandedFolderBackground-2sPsd-.collapsed-1GMuSb {
	border-radius: .25em !important;
}

.guilds-1SWlCJ .scroller-2TZvBN .listItem-2P_4kh div[class*='pill'], .tutorialContainer-SGrQ1h .pill-3YxEhL {
	height: 5px;
	top: -7px;
	left: 0px;
	width: 100%;
	transform: none;
	border-radius: .5em;
}

div[data-ref-id="guildsnav"]::-webkit-scrollbar-track {
	box-shadow: inset 0 0 6px rgba(0, 0, 0, 0.3);
}

div[data-ref-id="guildsnav"]::-webkit-scrollbar {
	width: .75rem;
}

div[data-ref-id="guildsnav"]::-webkit-scrollbar-thumb {
	border-radius: 2.5px 0 0 2.5px;
}

div[data-ref-id="guildsnav"]>div:first-child {
	margin-left: 0 !important
}

div[data-ref-id="guildsnav"]>.listItem-2P_4kh, div[data-ref-id="guildsnav"]>.wrapper-21YSNc {
	margin: 10px 0 5px 5px !important;
	max-height: var(--ServerSize);
}

div[data-ref-id="guildsnav"]>.wrapper-21YSNc {
	border-radius: .25em;
}

#app-mount .wrapper-21YSNc {
	width: auto !important;
	display: flex;
	align-items: center;
	margin-bottom: 0;
}

#app-mount .wrapper-21YSNc [role=group] {
	display: flex;
	align-items: center;
	height: auto !important;
	border-radius: 0 .25em .25em 0;
}

.guilds-1SWlCJ>.scrollerWrap-1IAIlv>.scroller-2TZvBN>.tutorialContainer-1v44GL, .guilds-1SWlCJ .scrollerWrap-1IAIlv .scroller-2TZvBN>.tutorialContainer-SGrQ1h, .guilds-1SWlCJ>.scrollerWrap-1IAIlv>.scroller-2TZvBN>div:last-child {
	background-color: transparent;
}

/* PMs */

.tutorialContainer-1v44GL {
	margin: 10px 0 0px 5px !important;
	max-height: var(--ServerSize);
	order: 0;
}

.tutorialContainer-SGrQ1h {
	margin-left: 5px !important;
}

.guilds-1SWlCJ .scrollerWrap-1IAIlv, .guilds-1SWlCJ>.scrollerWrap-1IAIlv>.scroller-2TZvBN {
	display: flex;
	contain: unset;
	width: 100%;
	height: calc(20px + var(--ServerSize));
}

.expandedFolderIconWrapper-1xLaU- {
	width: 100%;
	height: 100%;
}

.expandedFolderBackground-2sPsd- {
	min-height: var(--ServerSize);
	top: 0;
	left: 0;
	bottom: 0;
}

.guilds-1SWlCJ>.scrollerWrap-2lJEkd>.scroller-2TZvBN>.listItem-2P_4kh {
	background-color: var(--grey);
	margin-left: 5px !important;
	border-radius: .35em;
}

#app-mount .guilds-1SWlCJ .scroller-2TZvBN>div[style*="opacity: 1;"]:first-child {
	margin: 10px 5px 0 5px;
}

.tutorialContainer-SGrQ1h+.listItem-2P_4kh .pill-3YxEhL .wrapper-sa6paO, .tutorialContainer-SGrQ1h .pill-3YxEhL .wrapper-sa6paO, .item-2hkk8m {
	height: 5px !important;
	width: 100% !important;
	margin: 0 !important;
}

.unreadMentionsIndicatorTop-gA6RCh {
	padding: 0;
	height: 20px;
	width: var(--ServerSize);
	left: 15px;
	top: calc(15px + var(--ServerSize));
}

#app-mount .guilds-1SWlCJ .scroller-2TZvBN>div[style*="opacity: 1;"]:not(:first-child) {
	margin: 10px 0 0 5px;
	order: 1;
}

.tutorialContainer-SGrQ1h, .tutorialContainer-SGrQ1h+.listItem-2P_4kh {
	order: 2;
}

#app-mount [data-ref-id=guildsnav] {
	display: flex;
	flex-wrap: wrap;
	height: calc(10px + 10px * var(--ServerColumns) + var(--ServerSize) * var(--ServerColumns));
	overflow-y: auto;
	order: 3;
	width: 100%;
	justify-content: center;
}

.guilds-1SWlCJ .scroller-2TZvBN>.listItem-2P_4kh:first-child+.listItem-2P_4kh:not([style]), .guilds-1SWlCJ .scroller-2TZvBN>div[style]:not(.listItem-2P_4kh)+.listItem-2P_4kh {
	height: var(--ServerSize);
}

#bd-pub-li {
	margin: 10px 0 0 5px;
	overflow: hidden;
	min-width: var(--ServerSize);
	width: var(--ServerSize);
	height: var(--ServerSize);
}

#bd-pub-button {
	border-radius: .25em;
	background: url("https://cdn.discordapp.com/avatars/566695845098160128/a_d23f74b1cec4a5b0f706a8393477e630.gif?size=4096");
	color: #ffffff;
	font-size: 12px;
	background-size: 90% 90%;
	background-repeat: no-repeat;
	background-position: center;
}

.unreadMentionsIndicatorBottom-BXS58x {
	padding: 0;
	height: 25px;
	width: var(--ServerSize);
	left: 5px;
	top: calc(15px + var(--ServerSize));
}

.panels-j1Uci_>.container-3baos1 {
	border-radius: 0 5px 0 0;
}

.tutorialContainer-SGrQ1h+.listItem-2P_4kh {
	margin: 10px 5px 0 5px !important;
