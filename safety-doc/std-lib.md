| Pull Request | API | Info | Contributor |
| --- | --- | --- | --- |
| [155559](https://github.com/rust-lang/rust/pull/155559) | NonZero::unchecked_add, NonZero::unchecked_mul | Add safety section (syntax) | hxuhack |
| [155450](https://github.com/rust-lang/rust/pull/155450) | usize::unchecked_add, usize::unchecked_sub, usize::unchecked_mul | Remove unnecessary safety conditions | hxuhack |
| [154665](https://github.com/rust-lang/rust/pull/154665) | mem::uninitialized, mem::zeroed, mem::transmute_copy | Add safety section (syntax/semantic) | hxuhack |
| [154081](https://github.com/rust-lang/rust/pull/154081) | Rc::from_raw, Rc::from_raw_in, Arc::from_raw, Arc::from_raw_in | Add safety section (syntax) | hxuhack |
| [153384](https://github.com/rust-lang/rust/pull/153384) | CString::from_vec_unchecked, async_drop_in_place | Add safety section | hxuhack |
| [146925](https://github.com/rust-lang/rust/pull/146925) | VaListImpl::arg, intrinsic::va_copy, intrinsic::va_arg, intrinsic::va_end | Add safety section | ClearLove |
| [146870](https://github.com/rust-lang/rust/pull/146870) | Box::from_raw, Box::from_raw_in, Box::from_non_null, Box::from_non_null_in | Add missing safety preconditions | ClearLove |
| [138309](https://github.com/rust-lang/rust/pull/138309) | intrinsic::volatile_copy_nonoverlapping_memory, intrinsic::volatile_set_memory, intrinsic::typed_swap_nonoverlapping | Add safety section | ClearLove |
| [138303](https://github.com/rust-lang/rust/pull/138303) | Arc::increment_strong_count, Arc::decrement_strong_count, Arc::increment_strong_count_in, Arc::decrement_strong_count_in, Rc::increment_strong_count, Rc::decrement_strong_count, Rc::increment_strong_count_in, Rc::decrement_strong_count_in | Add missing safety preconditions | ClearLove |
| [137714](https://github.com/rust-lang/rust/pull/137714) | alloc::ffi::CStr::from_raw, alloc::str::from_boxed_utf8_unchecked | Add missing safety preconditions | ClearLove |
| [135805](https://github.com/rust-lang/rust/pull/135805) | Box::from_non_null, Box::from_non_null_in, Weak::from_raw | Add missing safety preconditions | ClearLove |
| [135009](https://github.com/rust-lang/rust/pull/135009) | Box::from_raw, Box::from_raw_in | Add missing safety preconditions | ClearLove |
| [134953](https://github.com/rust-lang/rust/pull/134953) | ptr::read_unaligned, ptr::write_unaligned | Add missing safety preconditions | ClearLove |
| [134496](https://github.com/rust-lang/rust/pull/134496) | Arc::from_raw, Arc::increment_strong_count, Arc::decrement_strong_count | Add missing safety preconditions | ClearLove |
| [158314](https://github.com/rust-lang/rust/pull/158314) | int::unchecked_div_exact | Fix incorrect unsafe debug assertion | yilin0518 |
| [158382](https://github.com/rust-lang/rust/pull/158382) | SliceIndex::get_unchecked(mut) | Add safety section (syntax)  | yilin0518 |
| [158433](https://github.com/rust-lang/rust/pull/158433) | VecDeque::nonoverlapping_ranges | Fix inconsistent safety requirement | yilin0518 |
| [158810](https://github.com/rust-lang/rust/pull/158810) | *const[T]::get_unchecked, NonNull<[T]>::get_unchecked_mut | Add supplementary information | yilin0518 |
| [2183](https://github.com/rust-lang/stdarch/pull/2183)  | _mm_stream_si32, _mm_stream_si64 | Add supplementary information | yilin0518 |
| [158804](https://github.com/rust-lang/rust/pull/158804) | *mut T::as_uninit_mut | Add supplementary information | yilin0518 |
| [159322](https://github.com/rust-lang/rust/pull/159322) | intrinsic::simd::simd_gather, intrinsic::simd::simd_scatter| Fix safety section | yilin0518 |
| [159402](https://github.com/rust-lang/rust/pull/159402) | intrinsic::simd::simd_shl/shr, intrinsic::simd::simd_funnel_shl/shr, intrinsic::simd::simd_masked_load, intrinsic::simd::simd_masked_store| Fix safety section | yilin0518 |

