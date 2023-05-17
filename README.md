# Potomo

Potomo compile `.po` file to `.mo` file in command line.

## Usage

```
potomo --finput <input_file.po> [--foutput <output_file.mo>] [--nmsg]
potomo --uninstall-library [--nmsg]
```

### Details

- `--finput <input_file.po>` : specify input filename.
- `--foutput <output_file.mo>` : specify output filename. The default name is the input filename with `.mo` extension.
- `--uninstall-library` : uninstall gettext library. This library is used to compile the `.po` file to `.mo` file.
- `--nmsg` : hide all output messages.
