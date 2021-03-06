# React Native Tag Input

![alt text](example.png "Example visual")

Simple Example

```
import TagInput from 'react-native-tag-input';

...

<TagInput
  value={this.state.emails}
  onChange={(emails) => this.onEmailChange(emails)} />
```

| Available Properties | Description |
-----------------------|-----------------
| onChange | (Required) A handler to be called when array of emails/tags change |
| value | (Required) An array of tags |
| regex | A RegExp to test tags after enter, space, or a comma is pressed |
| tagColor | Background color of tags |
| tagTextColor | Text color of tags |
| inputColor | Color of text input |
| inputProps | Any misc. TextInput props (autofocus, returnKeyType, etc.) |
| labelKey | String. Label key if tag is an object, (tag[labelKey]) |
| numberOfLines | number. Number of maximum lines of the tag input |
