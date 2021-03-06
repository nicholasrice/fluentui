## API Report File for "@fluentui/react-theme-provider"

> Do not edit this file. It is a report generated by [API Extractor](https://api-extractor.com/).

```ts

import { ComponentProps } from '@fluentui/react-utilities';
import { PartialTheme } from '@fluentui/react-theme';
import * as React_2 from 'react';
import { Theme } from '@fluentui/react-theme';
import { useTheme } from '@fluentui/react-shared-contexts';

// @public (undocumented)
export function renderThemeProvider(state: ThemeProviderState): JSX.Element;

// @public (undocumented)
export const ThemeProvider: React_2.ForwardRefExoticComponent<ThemeProviderProps & React_2.RefAttributes<HTMLElement>>;

// @public (undocumented)
export interface ThemeProviderProps extends ComponentProps, React_2.HTMLAttributes<HTMLElement> {
    targetDocument?: Document | undefined;
    // (undocumented)
    theme?: PartialTheme | Theme;
}

// @public (undocumented)
export const themeProviderShorthandProps: (keyof ThemeProviderProps)[];

// @public (undocumented)
export interface ThemeProviderState extends ThemeProviderProps {
    ref: React_2.MutableRefObject<HTMLElement>;
    // (undocumented)
    theme: Theme;
}

export { useTheme }

// @public
export const useThemeProvider: (props: ThemeProviderProps, ref: React_2.Ref<HTMLElement>, defaultProps?: ThemeProviderProps | undefined) => ThemeProviderState;


// (No @packageDocumentation comment for this package)

```
