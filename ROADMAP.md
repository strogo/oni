# Oni

## Roadmap

- 0.3
    - [ ] Extensibility models
        - [ ] Language service
            - [x] Autocompletion (TypeScript, Javascript)
            - [x] QuickInfo (TypeScript, JavaScript)
            - [x] Goto Definition (TypeScript, JavaScript)
            - [x] Errors
            - [x] Formatting
            - [ ] Documentation
            - [ ] Find-in-files
        - [ ] Integration with [language-server-protocol](https://github.com/Microsoft/language-server-protocol)
            - [ ] C# / OmniSharp integration
            - [ ] Python Integration
            - [ ] ReasonML Integration
    - [x] Configuration loading
    - [ ] Multiplexed UI + UI enhancements - Part 1
        - [ ] Tab UI
        - [ ] Status bar
    - [ ] Website at onivim.io
        - [ ] Youtube Demo
    - [ ] QuickOpen Improvements
        - [x] Config variable
        - [x] Non-git strategy
        - [x] Fuzzy Matching
        - [ ] Scrollbar
        - [x] Icon
- 0.4
    - [ ] Plugin Manager
    - [ ] Multiplexed UI + UI enhancements - Part 2
        - [ ] Window Manager
        - [ ] Removal of `Overlay`
        - [ ] 'Sneak Mode' like Vimium
        - [ ] Browser Tab
            - [ ] Markdown Preview
            - [ ] Open Browser Window
    - [ ] Better app icon
    - [ ] Left Pane
    - [ ] Animation support
        - [ ] Cursor animation
    - [ ] Performance improvements
        - [ ] Scroll performance improvement (avoid redraw)
        - [ ] Perceived performance - render characters instally in insert
    - [ ] Mouse support
        - [ ] Buffer scroll bars
        - [ ] Autocompletion scroll bars
        - [ ] QuickOpen scroll bars

- 0.5
    - [ ] AutoCompletion
        - [ ] Fuzzy Matching
    - [ ] CSS / LESS Language Server
    - [ ] HTML Language Server
    - [ ] Proper keymap support
    - [ ] Python language service plugin
    - [ ] ReasonML / OCaml language service plugin

- Future
    - [ ] Sidebar
        - [ ] File explorer
    - [ ] CSS Skins
    - [ ] Scrollbar minimap (a-la sublime)
    - [ ] Enhanced VimTutor
    - [ ] Katas
        - [ ] Functional programming katas
    - [ ] Collaborative app icon
    - [ ] Extensibility
        - [ ] Debugger support
        - [ ] Snippet support
    - [ ] Project templates

### Completed
    - 0.1
        - [x] Initial repo
        - [x] OS X / Windows support
        - [x] TypeScript language support
        - [x] Listing in NeoVim wiki
    - 0.2
        - [x] Services
            - [x] QuickOpen - Modern CTRL-P replacement
        - [x] Installation via NPM
            - [x] Handle case where NeoVim is not already installed
        - [x] Integration with popupmenu_external
        - [x] Windows Installer
        - [x] OSX Installer
