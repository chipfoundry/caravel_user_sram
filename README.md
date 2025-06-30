# Caravel User SRAM Example

This project demonstrates the straightforward integration of a commercial SRAM within the `user_project_wrapper` using the IPM (IP Manager) tool.

## Get Started Quickly

### Follow these steps to set up your environment and harden the SRAM:

1. **Clone the Repository:**

```
git clone https://github.com/efabless/caravel_user_sram.git
```
2. **Prepare Your Environment:**

```
cd caravel_user_sram
make setup
```
3. **Install IPM:**

```
pip install cf-ipm
```
4. **Install the SRAM IP:**

```
ipm install CF_SRAM_1024x32
```
5. **Harden the SRAM Macro:**

```
make CF_SRAM_1024x32_wb_wrapper
```
6. **Harden the User Project Wrapper:**

```
make user_project_wrapper
```

For further information on usage, consult the dedicated [knowledgebase article](https://chipfoundry.io/knowledge-base/commercial-sram). Details about the SRAM IP itself are available in the [SRAM documentation](https://chipfoundry.io/commercial-sram).


