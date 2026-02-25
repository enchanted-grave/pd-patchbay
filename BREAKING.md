# pd-patchbay

1) Group name is not anymore written with dot:

[patchbay.to~ pb group.node] -> [patchbay.to~ pb group node]
[patchbay.from~ pb group.node] -> [patchbay.from~ pb group node]

2) No more access to `destinations` and `sources` messages; setup can be done only with creating `patchbay.to~` and `patchbay.from~` objects.
