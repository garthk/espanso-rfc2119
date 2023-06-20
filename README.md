# Espanso Matches for RFC 2119

You [MAY] expand these matches into links to [RFC 2119].

> Authors who follow these guidelines [SHOULD] incorporate this phrase near the beginning
> of their document:
>
> The key words "[MUST]", "[MUST NOT]", "[REQUIRED][MUST]", "[SHALL][MUST]",
> "[SHALL NOT][MUST NOT]", "[SHOULD]", "[SHOULD NOT]", "[RECOMMENDED][SHOULD]", "[MAY]",
> and "[OPTIONAL][MAY]" in this document are to be interpreted as described in [RFC 2119].

To install this [external package][extpkg]:

```bash
espanso install espanso-rfc2119 \
    --git https://github.com/garthk/espanso-rfc2119 --external
```

Matches in this package include:

| label          | trigger | markdown                                                    |
| -------------- | ------- | ----------------------------------------------------------- |
| RFC 2119 intro | `;2119` | The key words "[MUST]", "[MUST NOT]", "[REQUIRED][MUST]"…   |
| MUST           | `;2mus` | [MUST](https://tools.ietf.org/html/rfc2119#section-1)       |
| MUST NOT       | `;2mno` | [MUST NOT](https://tools.ietf.org/html/rfc2119#section-2)   |
| SHOULD         | `;2sho` | [SHOULD](https://tools.ietf.org/html/rfc2119#section-3)     |
| SHOULD NOT     | `;2sno` | [SHOULD NOT](https://tools.ietf.org/html/rfc2119#section-4) |
| MAY            | `;2may` | [MAY](https://tools.ietf.org/html/rfc2119#section-5)        |

[RFC 2119]: https://tools.ietf.org/html/rfc2119
[MUST]: https://tools.ietf.org/html/rfc2119#section-1
[MUST NOT]: https://tools.ietf.org/html/rfc2119#section-2
[SHOULD]: https://tools.ietf.org/html/rfc2119#section-3
[SHOULD NOT]: https://tools.ietf.org/html/rfc2119#section-4
[MAY]: https://tools.ietf.org/html/rfc2119#section-5
[extpkg]: https://espanso.org/docs/packages/external-packages/
