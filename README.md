# VS-Code-Dark-Dimmed-and-CSS-file
VSCode 主题 现代深色强化版 附带CSS文件
```css
:root {
  --activityBar-activeBorder: #0078D4;
  --activityBar-background: #181818;
  --activityBar-border: #2B2B2B;
  --activityBar-foreground: #D7D7D7;
  --activityBar-inactiveForeground: #868686;
  --activityBarBadge-background: #0078D4;
  --activityBarBadge-foreground: #FFFFFF;
  --badge-background: #616161;
  --badge-foreground: #F8F8F8;
  --button-background: #0078D4;
  --button-border: #FFFFFF12;
  --button-foreground: #FFFFFF;
  --button-hoverBackground: #026EC1;
  --button-secondaryBackground: #313131;
  --button-secondaryForeground: #CCCCCC;
  --button-secondaryHoverBackground: #3C3C3C;
  --chat-slashCommandBackground: #34414B;
  --chat-slashCommandForeground: #40A6FF;
  --checkbox-background: #313131;
  --checkbox-border: #3C3C3C;
  --debugToolBar-background: #181818;
  --descriptionForeground: #9D9D9D;
  --dropdown-background: #313131;
  --dropdown-border: #3C3C3C;
  --dropdown-foreground: #CCCCCC;
  --dropdown-listBackground: #1F1F1F;
  --editor-background: #1F1F1F;
  --editor-findMatchBackground: #9E6A03;
  --editor-foreground: #CCCCCC;
  --editorGroup-border: #FFFFFF17;
  --editorGroupHeader-tabsBackground: #181818;
  --editorGroupHeader-tabsBorder: #2B2B2B;
  --editorGutter-addedBackground: #2EA043;
  --editorGutter-deletedBackground: #F85149;
  --editorGutter-modifiedBackground: #0078D4;
  --editorLineNumber-activeForeground: #CCCCCC;
  --editorLineNumber-foreground: #6E7681;
  --editorOverviewRuler-border: #010409;
  --editorWidget-background: #202020;
  --errorForeground: #F85149;
  --focusBorder: #0078D4;
  --foreground: #CCCCCC;
  --icon-foreground: #CCCCCC;
  --input-background: #313131;
  --input-border: #3C3C3C;
  --input-foreground: #CCCCCC;
  --input-placeholderForeground: #989898;
  --inputOption-activeBackground: #2489DB82;
  --inputOption-activeBorder: #2488DB;
  --keybindingLabel-foreground: #CCCCCC;
  --menu-background: #1F1F1F;
  --menu-selectionBackground: #0078d4;
  --notificationCenterHeader-background: #1F1F1F;
  --notificationCenterHeader-foreground: #CCCCCC;
  --notifications-background: #1F1F1F;
  --notifications-border: #2B2B2B;
  --notifications-foreground: #CCCCCC;
  --panel-background: #181818;
  --panel-border: #2B2B2B;
  --panelInput-border: #2B2B2B;
  --panelTitle-activeBorder: #0078D4;
  --panelTitle-activeForeground: #CCCCCC;
  --panelTitle-inactiveForeground: #9D9D9D;
  --peekViewEditor-background: #1F1F1F;
  --peekViewEditor-matchHighlightBackground: #BB800966;
  --peekViewResult-background: #1F1F1F;
  --peekViewResult-matchHighlightBackground: #BB800966;
  --pickerGroup-border: #3C3C3C;
  --progressBar-background: #0078D4;
  --quickInput-background: #222222;
  --quickInput-foreground: #CCCCCC;
  --settings-dropdownBackground: #313131;
  --settings-dropdownBorder: #3C3C3C;
  --settings-headerForeground: #FFFFFF;
  --settings-modifiedItemIndicator: #BB800966;
  --sideBar-background: #181818;
  --sideBar-border: #2B2B2B;
  --sideBar-foreground: #CCCCCC;
  --sideBarSectionHeader-background: #181818;
  --sideBarSectionHeader-border: #2B2B2B;
  --sideBarSectionHeader-foreground: #CCCCCC;
  --sideBarTitle-foreground: #CCCCCC;
  --statusBar-background: #181818;
  --statusBar-border: #2B2B2B;
  --statusBar-debuggingBackground: #0078D4;
  --statusBar-debuggingForeground: #FFFFFF;
  --statusBar-focusBorder: #0078D4;
  --statusBar-foreground: #CCCCCC;
  --statusBar-noFolderBackground: #1F1F1F;
  --statusBarItem-focusBorder: #0078D4;
  --statusBarItem-prominentBackground: #6E768166;
  --statusBarItem-remoteBackground: #0078D4;
  --statusBarItem-remoteForeground: #FFFFFF;
  --tab-activeBackground: #1F1F1F;
  --tab-activeBorder: #1F1F1F;
  --tab-activeBorderTop: #0078D4;
  --tab-activeForeground: #FFFFFF;
  --tab-selectedBorderTop: #6caddf;
  --tab-border: #2B2B2B;
  --tab-hoverBackground: #1F1F1F;
  --tab-inactiveBackground: #181818;
  --tab-inactiveForeground: #9D9D9D;
  --tab-unfocusedActiveBorder: #1F1F1F;
  --tab-unfocusedActiveBorderTop: #2B2B2B;
  --tab-unfocusedHoverBackground: #1F1F1F;
  --terminal-foreground: #CCCCCC;
  --terminal-tab-activeBorder: #0078D4;
  --textBlockQuote-background: #2B2B2B;
  --textBlockQuote-border: #616161;
  --textCodeBlock-background: #2B2B2B;
  --textLink-activeForeground: #4daafc;
  --textLink-foreground: #4daafc;
  --textPreformat-foreground: #D0D0D0;
  --textPreformat-background: #3C3C3C;
  --textSeparator-foreground: #21262D;
  --titleBar-activeBackground: #181818;
  --titleBar-activeForeground: #CCCCCC;
  --titleBar-border: #2B2B2B;
  --titleBar-inactiveBackground: #1F1F1F;
  --titleBar-inactiveForeground: #9D9D9D;
  --welcomePage-tileBackground: #2B2B2B;
  --welcomePage-progress-foreground: #0078D4;
  --widget-border: #313131;
}

.activityBar {
  border: 1px solid var(--activityBar-border);
  background-color: var(--activityBar-background);
}

.activityBar .active {
  border: 1px solid var(--activityBar-activeBorder);
}

.activityBarBadge {
  background-color: var(--activityBarBadge-background);
  color: var(--activityBarBadge-foreground);
}

.badge {
  background-color: var(--badge-background);
  color: var(--badge-foreground);
}

.button {
  background-color: var(--button-background);
  border: 1px solid var(--button-border);
  color: var(--button-foreground);
}

.button:hover {
  background-color: var(--button-hoverBackground);
}

.button.secondary {
  background-color: var(--button-secondaryBackground);
  color: var(--button-secondaryForeground);
}

.button.secondary:hover {
  background-color: var(--button-secondaryHoverBackground);
}

.chat {
  background-color: var(--chat-slashCommandBackground);
  color: var(--chat-slashCommandForeground);
}

.checkbox {
  background-color: var(--checkbox-background);
  border: 1px solid var(--checkbox-border);
}

.debugToolBar {
  background-color: var(--debugToolBar-background);
}

.description {
  color: var(--descriptionForeground);
}

.dropdown {
  background-color: var(--dropdown-background);
  border: 1px solid var(--dropdown-border);
  color: var(--dropdown-foreground);
}

.dropdown-list {
  background-color: var(--dropdown-listBackground);
}

.editor {
  background-color: var(--editor-background);
  color: var(--editor-foreground);
}

.editor-findMatch {
  background-color: var(--editor-findMatchBackground);
}

.editorGroup {
  border: 1px solid var(--editorGroup-border);
}

.editorGroupHeader {
  background-color: var(--editorGroupHeader-tabsBackground);
  border: 1px solid var(--editorGroupHeader-tabsBorder);
}

.editorGutter {
  background-color: var(--editorGutter-addedBackground);
}

.editorGutter.deleted {
  background-color: var(--editorGutter-deletedBackground);

```
