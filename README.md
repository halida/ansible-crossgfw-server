# crossgfw-server

## Usage

Clone to your roles folder as `crossgfw-server`, then in your playbooks file:

```yaml
  roles:
    - role: crossgfw-server
      ss_password: "{{ gfw.ss_password }}"
      kcp_password: "{{ gfw.kcp_password }}"
```
