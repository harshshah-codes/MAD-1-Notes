# More about Views in MVC

> Read more about [MVC](05%20Architectures%20of%20Software.md/#mvc-paradigm)

## Views and User Interfaces

A **View** consists of two components:

- User Interfaces
- User Interaction

### User Interfaces

#### Overview

User Interfaces are the design for interactions with the users. The goals of a good **user interface** are:

- The interface should be simple, i.e., easy for user to handle and understand.
- The interface should be efficient.
- The interface should be accessible to most of the users, i.e., it has some features for users with visual impairments, hearing impairments and so on.
- (**Optional**) The interface should be **asthetically pleasing**. The interface should not be filles with many colours or fonts. It should be simple and elegant.

!!! tip Extra

    A great article on guidelines for design: [Ten Usabilty Heuristics](https://nngroup.com/articles/ten-usability-heuristics/)

#### Creating a **good** UI

To create a good **user interface**, the following approach can be used:

- **Step 1**: Understand what are the needs for the potential client that will use the interface.
- **Step 2**: Create a **prototype** interface and present them to your clients.
- **Step 3**: After the approval of **prototype**, the interface should be given out to a small set of **potential users** for testing, that return feedback.

#### Examples

User Interfaces can be of many kinds. A few of them may be:

- Screen
- Audio
- Haptic feedback
- and so on....

### User Interactions

The devices through which a user can interact with the application are called user interaction devices.

They can be of many types. Some examples are:

- Keyboard/Mouse
- Audio Inputs
- Motor Inputs
- Custom Buttons

The user interactions are largely determined by **hardware constraints**. For e.g., you cannot access a desktop game that requires a mouse or keyboard on your mobile phone. To overcome this, **User-Agent** information can be used.

### Types of Views

There are many kinds of views:

- **Fully Static Web Pages**: These pages are completely static and do not require any computations on the client side. For example, the **about us** page on any website.
- **Partially Dynamic Web Pages**: These pages are partially dynamic and require some computations on the client side. For example, **a blog** which needs to fetch the posts but the headers and footers are static.
- **Mostly Dynamic Web Pages**: These pages are mostly dynamic and require a lot of computations on the client side. For example, **an ecommerce app**.
