# Clone.NetLoginPage

When you create a Blazor Server App and include authorization by default, you benefit from built-in pages like Login, Registration, and Log Out. These pages streamline the user registration, authentication, and authorization processes, saving a significant amount of development time.

While this is an excellent feature, I encountered a challenge when attempting to customize the Login page by removing certain layout elements. Unfortunately, I couldn't locate it in the Identity/Accounts folder. How can we address this issue?

To solve this, right-click on your project, select New -> Add Scaffolded Item, and then choose Identity from the menu on the left.

![Pic1](https://github.com/palakkalaslam/Clone.NetLoginPage/assets/13197706/17adf4b1-f6d0-49e4-9adb-4eaada22d485)

You will receive a catalog of pages within the solution that you have the option to override.

![Pic2](https://github.com/palakkalaslam/Clone.NetLoginPage/assets/13197706/5f9558ff-cc4e-4838-86ae-32f75a2adb2d)


Here, you have the option to either overwrite all the pages or selectively choose the ones that pique your interest. Afterward, you'll have the freedom to customize any of the selected pages.

However, exercise caution. If you decide to override the Log Out page, you might encounter some issues. You can find a resolution for this problem here.

For a more in-depth understanding of Blazor authentication and authorization, refer to the resources available on Microsoft Docs.
