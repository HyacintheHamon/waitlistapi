# React Component for getwaitlist.com (WaitlistAPI)

## Installation

`npm install waitlistapi`

or

`yarn add waitlistapi`

### Usage

```jsx
import React from 'react'
import { Waitlist } from 'waitlistapi'

const App = () => {
  return (
    <div>
      <Waitlist api_key="EXAMPLE" waitlist_link="https://example.com" />
    </div>
  )
}
```

### Props

| Prop                      | Type   | Default             | Definition                                                                               |
| ------------------------- | ------ | ------------------- | ---------------------------------------------------------------------------------------- |
| api_key                   | string | `required`          | The Waitlist API key found in your dashboard at getwaitlist.com                          |
| waitlist_link             | URL    | `required`          | The URL where your waitlist is hosted. Your referral codes will be appended to this URL. |
| joinWaitlistHeading       | string | `Get early access`  | Heading text shown in the join waitlist view (default)                                   |
| checkStatusHeading        | string | `Check your status` | Heading text shown in the check status view                                              |
| joinWaitlistButton        | string | `Join waitlist`     | Main button text shown in the join waitlist view                                         |
| checkStatusButton         | string | `Check status`      | Main button text shown in the check status view                                          |
| switchToCheckStatusLabel  | string | `Signed up before?` | Label shown below the main button                                                        |
| switchToCheckStatusLink   | string | `Check your status` | Link shown below the main button to switch views                                         |
| switchToJoinWaitlistLabel | string | `Not signed up?`    | Label shown below the main button                                                        |
| switchToJoinWaitlistLink  | string | `Join waitlist`     | Link shown below the main button to switch views                                         |
# waitlistapi
