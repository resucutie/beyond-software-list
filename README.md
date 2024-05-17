<p align="center"><img src="icon.svg"/></p>
<p align="center">
    <img src="https://img.shields.io/github/issues/abUwUser/beyond-software-list?style=for-the-badge&color=FF8702"/>
    <img src="https://img.shields.io/github/issues-pr/abUwUser/beyond-software-list?style=for-the-badge&color=FF8702"/>
    <a href="https://github.com/abUwUser/beyond-software"><img src="https://img.shields.io/badge/visit%20the%20website%20repo-FF8702?style=for-the-badge"/></a>
</p>
<h1 align="center">Beyond Software</h1>
<p align="center">
    A collective list of reliable and trustworthy software and resources for a better user expierence.<br>
    Not influenced by sponsors, advertisements or finnancial gain.
</p>

<br>

# How to Contribute
- Adding an issue requesting a new entry
- (preferred) Change [index.md](index.md) and make a Pull Request

Check the guidelines first [available on the webpage](https://beyondsoftware.info/#guidelines) or [directly at the file](index.md#guidelines).  
The whole list of software is available at [/public/assets/index.md](/public/assets/index.md).

**Please delete your forks after merging with the main repo. This is to prevent outdated information to be out in the wild**

# Running for dev/production enviorment
## Installing
1. Download [Git](https://git-scm.com/) and [Node](https://nodejs.org/)
2. `git clone https://github.com/abUwUser/beyond-software.git`
3. `cd beyond-software`
4. `npm i --global pnpm`
5. `pnpm i`
6. `git clone https://github.com/abUwUser/beyond-software-list.git ./docs`

## Building
Run `pnpm build` in the project folder to build the file. Sadly at the moment we do not provide any official way to watch for changes

For previewing, run `pnpm view-build`