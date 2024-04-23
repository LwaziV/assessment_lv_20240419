To successfully upgrade these applications then the below steps needs to be executed/followed.

1. Firstly, we need to ensure that we upgrade the shared library if it is not already running on .NET 8. and compatible with it.

    => All the packages that are installed in the shared library needs to be compatible with .NET 8. If some of the packages are not compatible with .NET 8 then each one of those packages needs to be upgraded.

    => Do thorough testing of the shared library to ensure that all of it's functionality is as expcted and nothing is breaking.

2. We then have to upgrade out applications, namely A, B and C.
    => We have to upgrade this 3 applications to .NET 8 so that the plugin can work well and be able to be shared across multiple applications (A,B,C and D).

    => For a successful upgrade, we need to ensure that the codebase is upgraded to the latest coding standards of .NET 8,
    if there is front-end codebase also needs to be upgraded to ensure that all of it's functionality is as expcted and nothing is breaking and the functions are able to reach the backend codebase successfully.

    => For an upgrade to be deemed successful, we need to ensure that thourough applications testing is conducted through out the application.

3. Minor changes to application D.
    => Even though Application D is running .NET 6, it is not far off from .NET 6, so upgrading this one last will save us a lot of time.
    => We may also need to update some package dependencies to ensure that everything package is compatible with .NET 8.
    => Do system testing to ensure a successful upgrade.

Releasing application.

Since we using containers and cloud environments, then we can release the application in phases to smaller environments and ensure that the application is running as expected.

Always have a backup of the application just incase you need to go back to the previous version.

If all goes well, then management will be informed and decide on a rollout date of the entire application.
