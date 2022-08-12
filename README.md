# React Native Code Snippets 🐱‍👤🐱‍🏍
Basic React Native Functional Component with Styled Components

## Settings
<p align="center">
  <img src="https://github.com/karenyov/react-native.code-snippets/blob/main/vscode.png" width="400">
</p>

## Code 
```sh
{
	"Basic React Native Functional Component": {
		"prefix": "rnfc",
		"body": [
			"import React from 'react';",
			"",
			"import {",
			"  Container",
			"} from './styles';",
			"",
			"export function ${TM_DIRECTORY/^.+\\\\(.*)$/$1/}(){",
			"  return (",
			"    <Container>",
			"",
			"    </Container>",
			"  );",
			"}"
		],
		"description": "Basic React Native Functional Component with Styled Components"
	},
	"Basic React Native Styled Component": {
		"prefix": "rnsc",
		"body": [
			"import styled from 'styled-components/native';",
			"",
			"export const Container = styled.View`",
			"  flex: 1;",
			"`;"
		],
		"description": "Basic Styled Component for React Native"
	},
}
```

# Screenshots
<p align="center">
  <img src="https://github.com/karenyov/react-native.code-snippets/blob/main/app.gif" width="400">
</p>

