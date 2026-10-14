## 0.2.0+12.ptech.1

 - **FIX**: use `SharedPreferencesAsync` for the non-secure persistence on native platforms. The legacy `SharedPreferences` cache no longer overwrites the keys that other `SharedPreferencesAsync` users write to the same file (Windows, Linux).
 - **BREAKING**: the `sharedPreferences` constructor parameter (legacy `SharedPreferences`) is replaced by `sharedPreferencesAsync` (`SharedPreferencesAsync`).
 - **FEAT**: on the default path, `init()` does a one-time, read-only migration of the keys under `storagePrefix` from the legacy store into `SharedPreferencesAsync`. Existing async values are not overwritten, and the legacy store is never written. Back-ported from upstream `oidc_default_store` 1.1.2.
 - **FIX**: concurrent `init()` calls share one pending initialization.

## 0.2.0+12

 - Update a dependency to the latest release.

## 0.2.0+11

 - Update a dependency to the latest release.

## 0.2.0+10

 - Update a dependency to the latest release.

## 0.2.0+9

 - Update a dependency to the latest release.

## 0.2.0+8

 - Update a dependency to the latest release.

## 0.2.0+7

 - Update a dependency to the latest release.

## 0.2.0+6

 - Update a dependency to the latest release.

## 0.2.0+5

 - Update a dependency to the latest release.

## 0.2.0+4

 - Update a dependency to the latest release.

## 0.2.0+3

 - Update a dependency to the latest release.

## 0.2.0+2

 - Update a dependency to the latest release.

## 0.2.0+1

 - Update a dependency to the latest release.

## 0.2.0

> Note: This release has breaking changes.

 - **BREAKING** **CHANGE**: all packages.

## 0.1.0+4

 - Update a dependency to the latest release.

## 0.1.0+3

 - Update a dependency to the latest release.

## 0.1.0+2

 - Update a dependency to the latest release.

# 0.1.0+1

- feat: initial commit 🎉
