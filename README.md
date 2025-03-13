# @palainteractive/capacitor-plugin-ios-webauth-session

This Capacitor plugin is designed to support Auth banking through our payment vendors. PayNearMe and VIP Preferred payment vendors currently require the Auth session component to launch their payment gateway on iOS.

## Install

```bash
npm install @palainteractive/capacitor-plugin-ios-webauth-session
npx cap sync
```

## API

<docgen-index>

* [`echo(...)`](#echo)
* [`startSession(...)`](#startsession)
* [`cancelSession()`](#cancelsession)

</docgen-index>

<docgen-api>
<!--Update the source file JSDoc comments and rerun docgen to update the docs below-->

### echo(...)

```typescript
echo(options: { value: string; }) => Promise<{ value: string; }>
```

| Param         | Type                            |
| ------------- | ------------------------------- |
| **`options`** | <code>{ value: string; }</code> |

**Returns:** <code>Promise&lt;{ value: string; }&gt;</code>

--------------------


### startSession(...)

```typescript
startSession(options: { urlString: string; returnUrlScheme: string; }) => Promise<{ result: string; }>
```

| Param         | Type                                                         |
| ------------- | ------------------------------------------------------------ |
| **`options`** | <code>{ urlString: string; returnUrlScheme: string; }</code> |

**Returns:** <code>Promise&lt;{ result: string; }&gt;</code>

--------------------


### cancelSession()

```typescript
cancelSession() => Promise<{ message: string; }>
```

**Returns:** <code>Promise&lt;{ message: string; }&gt;</code>

--------------------

</docgen-api>
