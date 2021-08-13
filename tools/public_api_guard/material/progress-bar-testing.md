## API Report File for "components-srcs"

> Do not edit this file. It is a report generated by [API Extractor](https://api-extractor.com/).

```ts

import { BaseHarnessFilters } from '@angular/cdk/testing';
import { ComponentHarness } from '@angular/cdk/testing';
import { HarnessPredicate } from '@angular/cdk/testing';

// @public
export class MatProgressBarHarness extends ComponentHarness {
    getMode(): Promise<string | null>;
    getValue(): Promise<number | null>;
    static hostSelector: string;
    static with(options?: ProgressBarHarnessFilters): HarnessPredicate<MatProgressBarHarness>;
}

// @public
export interface ProgressBarHarnessFilters extends BaseHarnessFilters {
}

// (No @packageDocumentation comment for this package)

```