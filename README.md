# Webtrekk Open Source Guidelines

The key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL NOT", "SHOULD", "SHOULD NOT", "RECOMMENDED",  "MAY", and "OPTIONAL" in this document are to be interpreted as described in [RFC 2119](http://www.ietf.org/rfc/rfc2119.txt)

## License
This Open Source Guidelines Project is publicly available and its usage and modification terms are written down in the [MIT LICENSE](LICENSE-MIT.md) document.

## Definition of a Project
A project in this guideline is a piece of code, script,  whole project, an executable software, how-to, documentation, solution to certain problem (not necessarily code)  that is considered to be open source.


## Open Source Project Candidate
Webtrekk is committed to contribute every tool and general purpose component to the community. What qualifies as tool or general purpose component is defined as follows:

* A tool is a program that is employed in the development, repair, or enhancement of other programs or of hardware as well as any program that can assist in all activities of all phases of the software life cycle, including management and quality-assurance activities. Thus a comprehensive set would address such issues as requirements specification, design, validation, configuration control, and project management. Examples of tools are a text editor, compiler, link loader, debugger.

* A general purpose component is any software component that solves a general problem of software engineering like layouting, rendering, encryption, file generation, compression etc. It MUST be possible to reuse the component without any knowledge about the Webtrekk system. Webtrekk MUST be able to incorporate the given component without any special changes.

Furthermore, the project SHOULD be tested automatically after each commit, and the code in the project SHOULD follow the company specific coding guidelines.


## Publishing Process Requirements
In order to define a proper process, which prevents harming Webtrekk's business and provides maximum clearity and visibility to all internal stake holders the following rules need to be applied to every project candidate:

* A named maintainer for the project MUST be willing to keep the issues list clean and answer to questions from contributors or users.

* At least one other person in the Webtrekk team MUST review the project prior to release.

* After release of the project, other developers in the company SHOULD be notified.

* The Webtrekk Tech Leads Board may decide on vetoing the project due to business interests. So candidate projects must be promoted for publishing. If no veto was spoken out, the maintainer is free to publish the project with respect to the rules given in this document.



## Distribution
* The project MUST be publicly available on a software development hosting service, in this case [github.com](http://github.com/Webtrekk) as project owned by the Webtrekk organization.
* The project MUST be licensed under [MIT](http://opensource.org/licenses/MIT), [LGPL 2.1](http://opensource.org/licenses/LGPL-2.1) or higher and every project MUST include license text in each text file and the main directory. Licence text can be found in this repository, please refer to [LICENSE-MIT.md](LICENSE-MIT.md) or [LICENSE-LGPL-2.1.md](LICENSE-LGPL-2.1.md).
* The project MUST have a properly formated README.md file (Github style) with references to license and further documentation.
* The project SHOULD have unit tests. A project that fails any unit tests SHOULD not be publicly available to anyone.
* Build automation tools SHOULD be used (e.g. sbt, maven, RubyGems, npm).
* Examples of usage SHOULD be provided.



## Versioning & Commit Messages
* Versioning standards SHOULD be applied to each project. 
[Semantic Versioning 2.0.0](http://semver.org/) SHOULD be used in every project.
* Each commit SHOULD have message that is clearly stating why the commit has been made.
* Commit messages SHOULD be 50 characters summary, following by empty space and description and finally issue code or ticket address.
for instance

```
Fixed bug of registration.

Here is the description. Lorem ipsum dolor sit amet,
consectetur adipiscing elit. Praesent tincidunt a 
purus id semper. Cras varius lectus sit amet massa
condimentum, ut porttitor est vulputate. 

[Issue #639]
```


## Documentation
* The project MUST have a README.md file for auto-generation of a README page.
* The code MUST carry name of the authors.
* The code SHOULD be well documented with relevant API documentation tools (e.g. JavaDoc, Doxygen).
* The project MAY have a wiki page, installation notes, change logs ([for instance](CHANGELOG.md)), known issues and bugs.
* The project MAY have an issue tracker.


## Contribution
We welcome community contributions, each project SHOULD contain relevant information regarding contributions rules. See [How to Contribute](CONTRIBUTING.md).


## Contributors
Each project MAY contain relevant information regarding contributors. See [Contributors](CONTRIBUTORS.md).


## Checklist
* Does it contain README file?
* Is a license file added to the project?
* Is the license text added to the code?
* Does it follow coding guidelines?
* Does it contain an appropriate amount of test?
* Does it use any automation tool?
* Does it contain API documentation?
* Does it contain at least one example of usage?
* Has it been reviewed by other team members?



