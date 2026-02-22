World's first n8n client that manage workflow collections inside VSCode/Cursor/Antigravity
- Walkthrough video: <a href="https://www.youtube.com/watch?v=1KgItvryNdA" target="_blank">n8n atom + Antigravity: vibe building workflow (feel like vibe coding)</a>
- Website: <a href="https://atom8n.com/" target="_blank">www.atom8n.com</a>
- Download the client extension: <a href="https://open-vsx.org/extension/atom8n/n8n-atom-v3" target="_blank">n8n Atom 3.0</a>
- Join Our Community: <a href="https://discord.gg/9MmAhtJFWW" target="_blank">Discord</a>, <a href="https://web.facebook.com/groups/atom8n" target="_blank">Facebook</a>
- Nodejs installation:
```
npx -y @atom8n/n8n@latest
```
Or docker:
```
docker volume create n8n_data

docker run --pull=always -it --rm --name n8n-atom -p 5888:5888 -v n8n_data:/home/node/.n8n atom8n/n8n:fork
```


<img width="2718" height="1618" alt="image" src="https://github.com/user-attachments/assets/8cc10306-e349-4cac-b5b7-e04cc9695ca0" />
<img width="2100" height="1358" alt="image" src="https://github.com/user-attachments/assets/6f53d124-27e8-45e2-935f-3933ad42ff12" />
<img width="2114" height="1496" alt="image" src="https://github.com/user-attachments/assets/c48534d1-742f-4981-b5eb-557f610015d2" />

## n8n Atom
n8n Atom is the world's first n8n client that manages workflow collections directly inside VSCode, Cursor, and Antigravity.

**Key Features:**
- File-Based Workflows: Convert n8n workflows into file format (.n8n) that can be committed to GitHub, enabling proper version control and collaboration
- Native Editor Integration: Full drag-and-drop n8n UI embedded directly in your editor, forked from the official n8n front-end
- AI-Powered Workflow Building: Leverage AI coding agents (like Antigravity) to iteratively build and improve workflows by editing the workflow JSON files directly
- Seamless Workflow Management: Create, edit, execute, and manage n8n workflows without leaving your development environment
- Local Development: Works with local n8n server instances, perfect for development and testing workflows before deploying to production

**Why n8n Atom?**
The main motivation behind this project was to make workflows file-based, so they can be committed to GitHub and version controlled like regular code. This also allows developers to leverage AI coding assistants to efficiently build and iterate on workflows, transforming the manual UI-based workflow creation process into a code-driven, version-controlled development experience.

**Perfect For:**
- Developers who want to version control their n8n workflows
Teams looking to integrate workflow development into their existing development workflow
- Users of Antigravity, Cursor, or VSCode who want a unified development environment
- Anyone who wants to leverage AI coding agents to build and improve workflows programmatically

## Story behind
As a developer working frequently with n8n workflows, I realized a core problem: **workflows couldn't be managed like code**.

**The problems I faced:**
- Workflows were stored in n8n's database, making version control impossible
- Every change required manual UI work, which was time-consuming and error-prone
- No way to review changes before deploying
- Couldn't leverage AI coding agents to build workflows automatically
- Had to switch between multiple tools, breaking my development flow

**The inspiration:**
I wanted to bring workflows into the file-based world so they could be committed to GitHub and version controlled like regular code. This would also allow developers to leverage AI coding assistants to efficiently build and iterate on workflows.

**The journey:**
I spent 2 days "vibe coding" with Antigravity to build the MVP. The experience was incredible, I could input 100% in natural language and build workflows seamlessly, just like coding. In those 2 days, I:
- Forked the front-end from the official n8n repository
- Integrated n8n UI into a VSCode extension
- Implemented a file-based workflow system (.n8n format)
- Created the world's first extension to manage n8n workflows in an editor

## Killing feature
<img alt="image" src="https://github.com/user-attachments/assets/8692fa68-c290-42f5-83ca-64c7b01f85b8" />


## Testimonials (for reference)
- "I've been waiting a long time for an extension like this, I think it's awesome"
- "Being able to version control workflows like regular code changes everything"
- "The workflow is incredibly powerful when used with other tools like Kanban and Thor Client"
- "This feels like you materialized the vision of turning VS Code into a true AI cockpit"
<img alt="image" src="https://github.com/user-attachments/assets/5ca3bb39-248f-407a-b5c5-6a09a261bc24" />
<img alt="image" src="https://github.com/user-attachments/assets/ee9d5d1c-8c62-475b-bf72-f677c061e25c" />
<img alt="image" src="https://github.com/user-attachments/assets/6f334782-ed50-40d6-9a78-43724dba0e85" />
<img alt="image" src="https://github.com/user-attachments/assets/c6d82899-9f05-4d56-9e5e-52f01aa58ef7" />


  


![Banner image](https://user-images.githubusercontent.com/10284570/173569848-c624317f-42b1-45a6-ab09-f0ea3c247648.png)

# n8n - Secure Workflow Automation for Technical Teams

n8n is a workflow automation platform that gives technical teams the flexibility of code with the speed of no-code. With 400+ integrations, native AI capabilities, and a fair-code license, n8n lets you build powerful automations while maintaining full control over your data and deployments.

![n8n.io - Screenshot](https://raw.githubusercontent.com/n8n-io/n8n/master/assets/n8n-screenshot-readme.png)

## Key Capabilities

- **Code When You Need It**: Write JavaScript/Python, add npm packages, or use the visual interface
- **AI-Native Platform**: Build AI agent workflows based on LangChain with your own data and models
- **Full Control**: Self-host with our fair-code license or use our [cloud offering](https://app.n8n.cloud/login)
- **Enterprise-Ready**: Advanced permissions, SSO, and air-gapped deployments
- **Active Community**: 400+ integrations and 900+ ready-to-use [templates](https://n8n.io/workflows)

## Quick Start

Try n8n instantly with [npx](https://docs.n8n.io/hosting/installation/npm/) (requires [Node.js](https://nodejs.org/en/)):

```
npx n8n
```

Or deploy with [Docker](https://docs.n8n.io/hosting/installation/docker/):

```
docker volume create n8n_data
docker run -it --rm --name n8n -p 5888:5888 -v n8n_data:/home/node/.n8n docker.n8n.io/n8nio/n8n
```

Access the editor at http://localhost:5888

## Resources

- 📚 [Documentation](https://docs.n8n.io)
- 🔧 [400+ Integrations](https://n8n.io/integrations)
- 💡 [Example Workflows](https://n8n.io/workflows)
- 🤖 [AI & LangChain Guide](https://docs.n8n.io/advanced-ai/)
- 👥 [Community Forum](https://community.n8n.io)
- 📖 [Community Tutorials](https://community.n8n.io/c/tutorials/28)

## Support

Need help? Our community forum is the place to get support and connect with other users:
[community.n8n.io](https://community.n8n.io)

## License

n8n is [fair-code](https://faircode.io) distributed under the [Sustainable Use License](https://github.com/n8n-io/n8n/blob/master/LICENSE.md) and [n8n Enterprise License](https://github.com/n8n-io/n8n/blob/master/LICENSE_EE.md).

- **Source Available**: Always visible source code
- **Self-Hostable**: Deploy anywhere
- **Extensible**: Add your own nodes and functionality

[Enterprise licenses](mailto:license@n8n.io) available for additional features and support.

Additional information about the license model can be found in the [docs](https://docs.n8n.io/sustainable-use-license/).

## Contributing

Found a bug 🐛 or have a feature idea ✨? Check our [Contributing Guide](https://github.com/n8n-io/n8n/blob/master/CONTRIBUTING.md) to get started.

## Join the Team

Want to shape the future of automation? Check out our [job posts](https://n8n.io/careers) and join our team!

## What does n8n mean?

**Short answer:** It means "nodemation" and is pronounced as n-eight-n.

**Long answer:** "I get that question quite often (more often than I expected) so I decided it is probably best to answer it here. While looking for a good name for the project with a free domain I realized very quickly that all the good ones I could think of were already taken. So, in the end, I chose nodemation. 'node-' in the sense that it uses a Node-View and that it uses Node.js and '-mation' for 'automation' which is what the project is supposed to help with. However, I did not like how long the name was and I could not imagine writing something that long every time in the CLI. That is when I then ended up on 'n8n'." - **Jan Oberhauser, Founder and CEO, n8n.io**

<img width="1038" height="1252" alt="image" src="https://github.com/user-attachments/assets/40399657-a371-4ed9-a232-4d100dccac5a" />

