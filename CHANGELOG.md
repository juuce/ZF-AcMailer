## CHANGELOG

### 7.2.0

**Enhancements:**

* [197: Add support for Expressive 3 via zend expressive renderer v2](https://github.com/acelaya/ZF-AcMailer/issues/197)

**Tasks:**

* [198: Improve build matrix so that it passes build for lowest and latest supported dependencies](https://github.com/acelaya/ZF-AcMailer/issues/198)

### 7.1.0

**Enhancements:**

* [186: Define a MailListenerTrait that can be used when it is not possible to extend AbstractMailListener](https://github.com/acelaya/ZF-AcMailer/issues/186)
* [185: Allow to register custom file attachment parsers](https://github.com/acelaya/ZF-AcMailer/issues/185)
* [194: Improve InvalidArgumentException::fromValidTypes message](https://github.com/acelaya/ZF-AcMailer/issues/194)
* [184: Include infection in the build process to improve tests](https://github.com/acelaya/ZF-AcMailer/issues/184)

**Tasks**

* [195: Include a docs dir with a docsify-powered documentation](https://github.com/acelaya/ZF-AcMailer/issues/195)
* [183: Drop support for PHP <7.1](https://github.com/acelaya/ZF-AcMailer/issues/183)

### 7.0.5

**Bugs**

* [192: Pre-render event is not properly registered when listeners are defined as services](https://github.com/acelaya/ZF-AcMailer/issues/192)

### 7.0.4

**Bugs**

* [190: It is no longer possible to preconfigure services before rendering the email since 7.0.3 was released](https://github.com/acelaya/ZF-AcMailer/issues/190)

### 7.0.3

**Bugs**

* [187: Make sure email templates are rendered before the PRE_SEND event is triggered](https://github.com/acelaya/ZF-AcMailer/issues/187)

### 7.0.2

**Bugs**

* [182: When an Email has a template, the result of rendering it should be set as the body](https://github.com/acelaya/ZF-AcMailer/issues/182)

### 7.0.1

**Tasks**

* [180: Increase phpstan level used in build matrix from 5 to 6](https://github.com/acelaya/ZF-AcMailer/issues/180)

**Bugs**

* [179: Make ExceptionInterface extend Throwable](https://github.com/acelaya/ZF-AcMailer/issues/179)
* [174: When using expressive and zend/view, a layout is configured for all templates. Make it not be used for emails](https://github.com/acelaya/ZF-AcMailer/issues/174)

### 7.0.0

**Enhancements:**

* [172: Improve quality on attachments business logic](https://github.com/acelaya/ZF-AcMailer/issues/172)
* [153: Add real compatibility with Zend expressive](https://github.com/acelaya/ZF-AcMailer/issues/153)
* [166: Allow preconfigured emails to extend among themeselves](https://github.com/acelaya/ZF-AcMailer/issues/166)
* [168: Drop controller plugin, forcing the MailService to be injected](https://github.com/acelaya/ZF-AcMailer/issues/168)
* [167: Allow listeners cancel email sending on preSend, by returning boolean false](https://github.com/acelaya/ZF-AcMailer/issues/167)
* [159: Completely rewrite the module, changing the focus, and making services truly stateless](https://github.com/acelaya/ZF-AcMailer/issues/159)
* [165: Create console migration tool, to migrate config from v5/v6 to v7](https://github.com/acelaya/ZF-AcMailer/issues/165)

**Tasks**

* [162: Add migration guide, explaining how to migrate form version 6 to 7](https://github.com/acelaya/ZF-AcMailer/issues/162)
* [169: Update documentation to explain new features and configuration structure](https://github.com/acelaya/ZF-AcMailer/issues/169)
* [163: Create gitattributes defining elements to exclude when installing package from dist](https://github.com/acelaya/ZF-AcMailer/issues/163)
* [157: Improve coding standards strictness by using slevomat/coding-standard](https://github.com/acelaya/ZF-AcMailer/issues/157)
* [170: Extract mailviewrenderer creation to a specific factory](https://github.com/acelaya/ZF-AcMailer/issues/170)
* [155: Use ::class magic constant whenever possible](https://github.com/acelaya/ZF-AcMailer/issues/155)
* [154: Drop PHP 5 support](https://github.com/acelaya/ZF-AcMailer/issues/154)
* [160: Remove everything which was deprecated](https://github.com/acelaya/ZF-AcMailer/issues/160)
* [161: Remove config migration from AcMailer 4.5 and earlier to AcMailer 5.0](https://github.com/acelaya/ZF-AcMailer/issues/161)

**Bugs:**

* [173: Make sure the charset is applied to all parts of the email body](https://github.com/acelaya/ZF-AcMailer/issues/173)
* [171: Ensure proper filename is discovered when adding an attachment without providing a name](https://github.com/acelaya/ZF-AcMailer/issues/171)

### 6.4.0

**Enhancements:**

* [144: Improve file attachment strategies](https://github.com/acelaya/ZF-AcMailer/issues/144)

### 6.3.1

**Tasks**

* [143: Add php 7.1 to build matrix and drop hhvm](https://github.com/acelaya/ZF-AcMailer/issues/143)

**Bugs:**

* [142: Events with ZF3 doesn't work](https://github.com/acelaya/ZF-AcMailer/issues/142)

### 6.3.0

**Enhancements:**

* [135: Added header encoding option](https://github.com/acelaya/ZF-AcMailer/pull/135)

### 6.2.0

**Enhancements:**

* [130: Added ConfigProvider support](https://github.com/acelaya/ZF-AcMailer/pull/130)
* [133: Added replyTo support in controller plugin](https://github.com/acelaya/ZF-AcMailer/pull/133)

### 6.1.0

**Enhancements:**

* [129: Make module installable via zend-component-installer](https://github.com/acelaya/ZF-AcMailer/pull/129)

### 6.0.0

**Enhancements:**

* [103: Drop support for the mail_options top-level configuration key](https://github.com/acelaya/ZF-AcMailer/issues/103)
* [124: Update to ZF3 components](https://github.com/acelaya/ZF-AcMailer/issues/124)

**Tasks**

* [126: Drop Support for PHP 5.5](https://github.com/acelaya/ZF-AcMailer/issues/126)

### 5.2.1

**Bugs:**

* [125: False is unsupported SSL type](https://github.com/acelaya/ZF-AcMailer/issues/125)

### 5.2.0

**Enhancements:**

* [104: Allow to define the Renderer to be used for each service](https://github.com/acelaya/ZF-AcMailer/issues/104)

**Tasks**

* [114: Drop Support for PHP 5.4](https://github.com/acelaya/ZF-AcMailer/issues/114)

### 5.1.1

**Bugs:**

* [113: The extends property is mapped when its value is null, making the MailOptions to throw an exception](https://github.com/acelaya/ZF-AcMailer/issues/113)

### 5.1.0

**Enhancements:**

* [110: ReplyTo message option is missing in configuration](https://github.com/acelaya/ZF-AcMailer/issues/110)
* [112: Document replyTo and replyToName config options](https://github.com/acelaya/ZF-AcMailer/issues/112)

**Tasks**

* [108: Remove the whole framework as a dev dependency](https://github.com/acelaya/ZF-AcMailer/issues/108)

### 5.0.1

**Bugs:**

* [105: The EVENT_MAIL_PRE_SEND event should be triggered before the files are attached to the email](https://github.com/acelaya/ZF-AcMailer/issues/105)

### 5.0.0

**Enhancements:**

* [66: Allow to register multiple mail services, each one consuming its own configuration](https://github.com/acelaya/ZF-AcMailer/issues/66)
* [77: Remove autoloader files and support only composer installation method](https://github.com/acelaya/ZF-AcMailer/issues/77)
* [67: Group related config in common groups](https://github.com/acelaya/ZF-AcMailer/issues/67)
* [82: Merge mail_adapter and mail_adapter_service configuration options into a single one, and make the factory to check if it is a service or not](https://github.com/acelaya/ZF-AcMailer/issues/82)
* [75: Allow to define charset to be used in email body when it is set via template](https://github.com/acelaya/ZF-AcMailer/issues/75)
* [78: Allow a base layout to be defined for all the emails](https://github.com/acelaya/ZF-AcMailer/issues/78)
* [84: Allow to define event managers at configuration level](https://github.com/acelaya/ZF-AcMailer/issues/84)
* [85: Improve code coverage after broken tests are fixed](https://github.com/acelaya/ZF-AcMailer/issues/85)
* [86: Add new configuration structure to the documentation](https://github.com/acelaya/ZF-AcMailer/issues/86)
* [91: Fix PHP 7 build](https://github.com/acelaya/ZF-AcMailer/issues/91)

**Tasks**

* [74: Set minimum PHP version to 5.4](https://github.com/acelaya/ZF-AcMailer/issues/74)
* [79: Change license to MIT](https://github.com/acelaya/ZF-AcMailer/issues/79)
* [69: Remove deprecated methods](https://github.com/acelaya/ZF-AcMailer/issues/69)
* [87: Mark setSubject method in MailServiceInterface as deprecated](https://github.com/acelaya/ZF-AcMailer/issues/87)
* [73: Improve code quality](https://github.com/acelaya/ZF-AcMailer/issues/73)
* [89: Add PHP 7 to travis configuration](https://github.com/acelaya/ZF-AcMailer/issues/89)
* [80: Add BC break warning between 5.0 and previous versions in README](https://github.com/acelaya/ZF-AcMailer/issues/80)
* [68: Create a changelog file and list changes in github releases too](https://github.com/acelaya/ZF-AcMailer/issues/68)
* [90: Create CLI entry point to migrate old config to new config](https://github.com/acelaya/ZF-AcMailer/issues/90)

### 4.5.1

**Bugs**:

* [96. Fix errors introduced with ZF 2.3.9 and 2.4.2](https://github.com/acelaya/ZF-AcMailer/issues/97)

### 4.5.0

**Enhancements:**

* [64: Create a controller plugin to access mail service](https://github.com/acelaya/ZF-AcMailer/issues/64)

**Bug fixes:**

* [65: Fixed UTF-8 problems when sending email with attachments](https://github.com/acelaya/ZF-AcMailer/issues/65)
* [70: Make sure multipart messages with attachments are properly working](https://github.com/acelaya/ZF-AcMailer/issues/70)

**Tasks:**

* [71: Replace usages of Zend\Mime objects with aliases by the original name with the Mime namespace](https://github.com/acelaya/ZF-AcMailer/issues/71)
* [72: Refactor code to be more coherent](https://github.com/acelaya/ZF-AcMailer/issues/72)
* [53: Improve code quality](https://github.com/acelaya/ZF-AcMailer/issues/53)
